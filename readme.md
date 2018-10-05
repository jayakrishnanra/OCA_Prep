**`Identifiers`**

* Should start with letters, currency symbols or combining characters
Can use Unicode characters, currency symbols and combining characters

**`Keywords`**

* assert introduced in java 1.4, and enum in 1.5
strictfp

**`Classes`**

* the order should be package, import and class name
* only one public class per file and file name should be same as class name
* main methods can use var args.

**`Compilation`**

* javac @argfiles where argfile could be multiple files with options and source file names e.g.
* javac @options @classes

* static imports have syntax 'import static'

**`Class Declaration and Modifiers`**

`Access Modifiers` - public, protected and private
`Nonaccess modifiers` - strictfp, final and abstract

* Four access controls - including default/package access but only three access modifiers
* Class can be public or default
* Protected has the same access limit as default i.e. package private but is also accessible from sub classes
* Marking class as protected is same as leaving it as default as it can't be accessed outside the package

`Interfaces`

default methods can't be private, protected, static, final or strictfp
static methods can't be final or strictfp
