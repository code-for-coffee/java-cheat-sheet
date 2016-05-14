# Java Cheat Sheet

Handy dandy Java cheat sheet.

##### Contents

* [Reserved Words](#reserved-words)
* [Operators](#operators)
* [Primitive Data Types](#primitive-data-types)
* [Labeled Statements](#labeled-statements)
* [Try with Resources](#try-with-resources)


## Reserved Words

These words cannot be used in variable naming because Java itself uses them. They _may_ look familiar!

```java
abstract
assert
boolean
break
byte
case
catch
char
class
const
continue
default
do
double
else
enum
extends
false
final
finally
float
for
goto
if
implements
import
instanceof
int
interface
long
native
new
null
package
private
protected
public
return
short
static
scrictfp
super
switch
syncronized
this
throw
throws
transient
true
try
void
volatile
while
```

## Operators

```java
+
+=
=
!
-
-=
==
~
*
*=
!=
&&
/
/=
<
||
%
%=
<=
++
&
&=
>
--
|
|=
>=
?
^
^=
:
<<
>>
>>>
<<=
>>=
>>>=
->
```

## Primitive Data Types

```java
boolean // default: is false
char    // default: \u0000
byte    // default: 0
short   // default: 0
int     // default: 0
long    // default: 0
float   // default: 0.0
double  // default: 0.0
```

>> **Note**: `String` is _not_ considered to be a default data type since it is composed of multiple `char`

## Labeled Statements

```java
rowLoop: for (int r = 0; r < rows.length; r++) {
  columnLoop: for (int c = 0; c < columns.length; c++) {
    break rowLoop;
  }
}
```

## Try with Resources

Exactly the same as then `using` statement in C#.

```java
try (FileReader reader = new FileReader()) {
  //reader.methodName();
}
```
