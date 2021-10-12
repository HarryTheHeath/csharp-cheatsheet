# CSharp Cheat Sheet Template

Keyword |                  Summary                   | Sample Code | Mentioned In
------- | ------------------------------------------ | ------------ | ------------
`;`     | Used to separate statements from each other | `int i = 5; i++; Console.WriteLine(i);` | [Script Execution](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#0-script-execution)
`//`    | Used for single-line comments              | `float multiplier = 0.01f; // % to float (e.g. 24% = 0.24)` | [Comments](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#single-line-comments)
Variable Initialization | When a value is assigned to a variable for the first time | `int a = 5;` | [Variables](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#variable-initialization)
`dotnet new console -o project-name` | For creating a new project using command prompt | `dotnet new console -o csharp-cheatsheet` | [Console Basics Intro](https://github.com/forsbergsskola-se/gp21-21-0927-csharp-basics-nim-HarryTheHeath/blob/main/assignments/003.3.1-console-basics-1.md#assignments-00331-console-basics-1)
Script Execution Order | Be mindful of chronology e.g. Maths | N/A | N/A
Formatting | ? | ? | ?
`Console.WriteLine` | Write a comment in command. Use for testing & instructions. | `CW + TAB` | [Printing Output](https://github.com/forsbergsskola-se/gp21-21-0927-csharp-basics-nim-HarryTheHeath/blob/main/assignments/003.3.1-console-basics-1.md#1---printing-output)
`Console.Write` | Doesn't create new line. Can chain multiple together. | `Console.Write("Ouput");` | [Comments](https://github.com/forsbergsskola-se/gp21-21-0927-csharp-basics-nim-HarryTheHeath/blob/main/assignments/003.3.1-console-basics-1.md#2---comments)
Multi-Line Comment | Turn more than one line of code into a comment | `/* Lines of text */` | [Comments](https://github.com/forsbergsskola-se/gp21-21-0927-csharp-basics-nim-HarryTheHeath/blob/main/assignments/003.3.1-console-basics-1.md#2---comments)
XML Documentation Comment | Use three forward slashes for special comments | `/// <summary> /// details` | [Comments](https://github.com/forsbergsskola-se/gp21-21-0927-csharp-basics-nim-HarryTheHeath/blob/main/assignments/003.3.1-console-basics-1.md#2---comments)
Variable | Data storage units that consist of a name & a type. | `int x = 1; Console.WriteLine(x);` | [Variables](https://github.com/forsbergsskola-se/gp21-21-0927-csharp-basics-nim-HarryTheHeath/blob/main/assignments/003.3.1-console-basics-1.md#3---variables)
Variable Declaration | Always declare a variable before using one | `int x; int y; int z; ` | [Variables](https://github.com/forsbergsskola-se/gp21-21-0927-csharp-basics-nim-HarryTheHeath/blob/main/assignments/003.3.1-console-basics-1.md#3---variables)
Variable Assignment | Use = sign to assign values to variables | `int z = (5+y)` | [Variables](https://github.com/forsbergsskola-se/gp21-21-0927-csharp-basics-nim-HarryTheHeath/blob/main/assignments/003.3.1-console-basics-1.md#3---variables)
Uninitialized Variable | A variable that's declared, but lacks a definite assigned value | `int k; k = k + 1;` | [Variables](https://github.com/forsbergsskola-se/gp21-21-0927-csharp-basics-nim-HarryTheHeath/blob/main/assignments/003.3.1-console-basics-1.md#3---variables)
`=` (Assignment Operator) | Assigns value to a variable, property, or indexer element. | `a = (b = c)` | [Variables](https://github.com/forsbergsskola-se/gp21-21-0927-csharp-basics-nim-HarryTheHeath/blob/main/assignments/003.3.1-console-basics-1.md#3---variables)
Scope | Three levels: Class, Method, & Block level | `public class ClassLevel { everythingElse }` | N/A
Variable Scope | The reacha & validity of a variable | `{This.variableScope}` | [Variables](https://github.com/forsbergsskola-se/gp21-21-0927-csharp-basics-nim-HarryTheHeath/blob/main/assignments/003.3.1-console-basics-1.md#3---variables)
`int` | Integer: whole numbers | `postive: 1, negative : -1` | [Basic Data Types](https://github.com/forsbergsskola-se/gp21-21-0927-csharp-basics-nim-HarryTheHeath/blob/main/slides/003.3.1-console-basics-1.md#4-basic-data-types)
`float` | Fractional numbers + f (floating point numericals) | `0.25f` | [Basic Data Types](https://github.com/forsbergsskola-se/gp21-21-0927-csharp-basics-nim-HarryTheHeath/blob/main/slides/003.3.1-console-basics-1.md#4-basic-data-types)
`double` | Less accurate than float, but better performance & fractionals | `double a = 12.3; double bacteriaSize = 24e-10;` | [Basic Data Types](https://github.com/forsbergsskola-se/gp21-21-0927-csharp-basics-nim-HarryTheHeath/blob/main/slides/003.3.1-console-basics-1.md#4-basic-data-types)
`bool` | True or false literal flags | `bool check = true; bool isWinning = false;` | [Basic Data Types](https://github.com/forsbergsskola-se/gp21-21-0927-csharp-basics-nim-HarryTheHeath/blob/main/slides/003.3.1-console-basics-1.md#4-basic-data-types)
`char` | Uses unicode for single characters | `char euroSign = "€"; foreach(char c in helloWorld) {}` | [Basic Data Types](https://github.com/forsbergsskola-se/gp21-21-0927-csharp-basics-nim-HarryTheHeath/blob/main/slides/003.3.1-console-basics-1.md#4-basic-data-types)
`string` | A full string | `string name = "Harry"; use "@" before quotations for multiline` | [Basic Data Types](https://github.com/forsbergsskola-se/gp21-21-0927-csharp-basics-nim-HarryTheHeath/blob/main/slides/003.3.1-console-basics-1.md#4-basic-data-types)
`byte` | Assign variable within byte data range | `byte value1 = 64; byte someByte = 0xF1;` | [Basic Data Types](https://github.com/forsbergsskola-se/gp21-21-0927-csharp-basics-nim-HarryTheHeath/blob/main/slides/003.3.1-console-basics-1.md#4-basic-data-types)
Implicit Casting | Give a direct value | `int i = 5; double d = 1; 5.0 d = 9.78;` | [Conversion](https://github.com/forsbergsskola-se/gp21-21-0927-csharp-basics-nim-HarryTheHeath/blob/main/slides/003.3.1-console-basics-1.md#5-conversion)
Explicit Casting | Converting fractional to whole comes with a loss of precision | `i = (int) d; // new value: 9 // string input = "2";` | [Conversion](https://github.com/forsbergsskola-se/gp21-21-0927-csharp-basics-nim-HarryTheHeath/blob/main/slides/003.3.1-console-basics-1.md#5-conversion)
Type Conversion | Convert between types e.g. class to variable  | `int num = 2147483647; long bigNum = num;` | [Conversion](https://github.com/forsbergsskola-se/gp21-21-0927-csharp-basics-nim-HarryTheHeath/blob/main/slides/003.3.1-console-basics-1.md#5-conversion)
`Convert.ToInt32` | Convert to int e.g. from input | `i = Convert.ToInt32(input);` | [Conversion](https://github.com/forsbergsskola-se/gp21-21-0927-csharp-basics-nim-HarryTheHeath/blob/main/slides/003.3.1-console-basics-1.md#5-conversion)
Operators | Functions represented as symbols | `int add = 3 + 5;` | [Operators](https://github.com/forsbergsskola-se/gp21-21-0927-csharp-basics-nim-HarryTheHeath/blob/main/slides/003.3.1-console-basics-1.md#7-operators)
Arithmetic Operators | Math operations | `public class Coin { public static Coins operator+ (Coin a, Coin b) {return new Coins (a, b);}` | [Operators](https://github.com/forsbergsskola-se/gp21-21-0927-csharp-basics-nim-HarryTheHeath/blob/main/slides/003.3.1-console-basics-1.md#7-operators)
`+` | add | `int add = 3 + 5; // 8` | [Operators](https://github.com/forsbergsskola-se/gp21-21-0927-csharp-basics-nim-HarryTheHeath/blob/main/slides/003.3.1-console-basics-1.md#7-operators)
`-` | sub | `int sub = 6 - 12; // -6 | [Operators](https://github.com/forsbergsskola-se/gp21-21-0927-csharp-basics-nim-HarryTheHeath/blob/main/slides/003.3.1-console-basics-1.md#7-operators)
```*``` | multiply | `int mul = 3 * 4; // 12` | [Operators](https://github.com/forsbergsskola-se/gp21-21-0927-csharp-basics-nim-HarryTheHeath/blob/main/slides/003.3.1-console-basics-1.md#7-operators)
`/` | divide | `int div = 9 / 3; // 3` | [Operators](https://github.com/forsbergsskola-se/gp21-21-0927-csharp-basics-nim-HarryTheHeath/blob/main/slides/003.3.1-console-basics-1.md#7-operators)
`%` | modulus | `int mod = 10 % 3; // = 1`| [Operators](https://github.com/forsbergsskola-se/gp21-21-0927-csharp-basics-nim-HarryTheHeath/blob/main/slides/003.3.1-console-basics-1.md#7-operators)
`+=` | assignment operator 1 | `a+=b -> a=a+b` | assignment operator 1 | [Operators](https://github.com/forsbergsskola-se/gp21-21-0927-csharp-basics-nim-HarryTheHeath/blob/main/slides/003.3.1-console-basics-1.md#7-operators)
`-=` | assignment operator 2 | `a−=b ->	a=a−b` | assignment operator 1 | [Operators](https://github.com/forsbergsskola-se/gp21-21-0927-csharp-basics-nim-HarryTheHeath/blob/main/slides/003.3.1-console-basics-1.md#7-operators)
`++` | incraments by 1 | `x++=11`  | assignment operator 1 | [Operators](https://github.com/forsbergsskola-se/gp21-21-0927-csharp-basics-nim-HarryTheHeath/blob/main/slides/003.3.1-console-basics-1.md#7-operators)
`--` | decraments by 1 | `double a = 1.5; cw (--a); // output: 0.5 | assignment operator 1` | [Operators](https://github.com/forsbergsskola-se/gp21-21-0927-csharp-basics-nim-HarryTheHeath/blob/main/slides/003.3.1-console-basics-1.md#7-operators)
Post-Increment `i++` | increment the value then use it inside the expression | `int a, b = 15; a = b++;` | [Operators](https://github.com/forsbergsskola-se/gp21-21-0927-csharp-basics-nim-HarryTheHeath/blob/main/slides/003.3.1-console-basics-1.md#7-operators)
Pre-Increment `++i` | increment the value of a variable before using it in an expression |  `int a, b = 15; a = ++b;` | [Operators](https://github.com/forsbergsskola-se/gp21-21-0927-csharp-basics-nim-HarryTheHeath/blob/main/slides/003.3.1-console-basics-1.md#7-operators)
`System.Math` | A static class for solving math problems | `System.Math` | [Math](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#8-math)
`static` | Something that can't be initiated or inherited | `static void Main() {}` | [Math](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#8-math)
`Math.Max` | Finds the highest value | `int max = Math.Max(5, 3); // = 5` | [Math](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#8-math)
`Math.Min` | Find the lowest value | `int min = Math.Min(5, 3); // = 3` | [Math](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#8-math)
`Math.Sqrt` | Squareroot (what multiplied by itself equals this number) | `double sqrt = Math.Sqrt(16); // 4.0, because 4 * 4 = 16` | [Math](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#8-math)
`Math.Abs` | Absolute (always positive, good for distance) | `double abs = Math.Abs(-4.3); // 4.3` | [Math](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#8-math)
`Math.Round` | Uses statistical rounding to round to the nearest integer | `double round = Math.Round(12.6); // 13` | [Math](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#8-math)
`Math.Floor` | Rounds to the lower integer | `double floor = Math.Floor(12.6) // 12`| [Math](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#8-math)
`Math.Ceiling` | Rounds to the higher integer | `double ceil = Math.Ceiling(12.1); // 13` | [Math](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#8-math)
`Math.Clamp` | Clamps an int between two defined values | `double clamp = Math.Clamp(15, 0, 10); // 15 is clamped to 10 ` | [Math](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#8-math)
`Math.Pow` | Returns the value to the power of power | `double pow = Math.Pow(2, 3); // 8 (2^3 = 2 * 2 * 2 = 8)` | [Math](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#8-math)
`string.Length` | Returns the numerical length of a string | `string length = firstName.Length;` | [Strings](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#9-strings)
`string.ToUpper` | Turns a string into ALL-CAPS. ToLower does the opposite. | `string upper = firstName.ToUpper(); // JOHN` | [Strings](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#9-strings)
`string.+` | String strings together |  `string fullName = firstName + " " + lastName; // John Kane` [Strings](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#9-strings)
`$"{}"` | String strings and variables together using interpolation | `string interp = $"{firstName} {lastName}"; // John Kane` | [Strings](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#9-strings)
`string.[]` | Get a certain letter or character from a string e.g. initials | `char char1 = firstName[0]; // 'J'` | [Strings](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#9-strings)
`string.IndexOf` | Get an index of a first occurence of a character or string | `int index = firstName.IndexOf("h"); // 2` | [Strings](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#9-strings)
`string.SubString(int)` | Get a subpart of a string starting at an inputted value | `string sub = firstName.SubString(1); // "ohn"` | [Strings](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#9-strings)
`string.Substring(int, int)` | Get a subpart of a string starting here, up until this length | `string sub = firstName.SubString(1, 2); // "oh"
` | [Strings](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#9-strings)
`string.Replace` | Replace all occurences of a character with another | `string replace = fullName.Replace( 'n', 'd'); // "Johd Kade"` | [Strings](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#9-strings)
immutable | Something that can never be changed | `string fullName = "John Kane"; fullName = fullName.Replace('n', 'd'); cw(fullName); // Johd Kade` | [Strings](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#9-strings)
Logical Operators | Logical constants used to connect two or more formulas | `Three types: and , or , and not ` | [Logical Operators](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#logical-operators)
`!` | Inverse a logical operator | `!false -> true` | [Logical Operators](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#logical-operators)
`&&` | Combine two bool values [AND]  | `bool x = true; bool y = true; bool z = x && y = true; // true` | [Logical Operators](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#logical-operators)
Comparison Operators | Compare two values to return a bool | `Equal to, greater than, less than etc.` | [Comparison Operators](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#comparison-operators)
`>` | Greater than | `bool isGreater = 10 > 9; // True` | [Comparison Operators](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#comparison-operators)
`==` | Is equal to | `bool isEqual = 10 == 9; // False` | [Comparison Operators](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#comparison-operators)
`!=` | IS NOT equal to | `bool isNotEqual = 10 != 9; // True` | [Comparison Operators](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#comparison-operators)
<code>&#124;&#124;</code> | Check if one of several values is true or false | `bool x = true; bool y = false; bool z = x && y = true; // true` | [Logical Operators](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#logical-operators)
`>=` | Greater OR equal to | `bool isGreaterOrEqual = 10>= 9; // True` | [Comparison Operators](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#comparison-operators)
`<=` | ? | `bool isLowerOrEqual = 10<= 9; // False` | ?
`if` | ? | ? | ?
`else` | ? | ? | ?
`else if` | ? | ? | ?
`? :` | ? | ? | ?
Flow Control Statements | ? | ? | ?
`System.Random` | ? | ? | ?
pseudo-random | ? | ? | ?
seed | ? | ? | ?
`Random.Next(int, int)` | ? | ? | ?
`Random.Next()` | ? | ? | ?
`Random.NextDouble()` | ? | ? | ?
`Random.Next()` | ? | ? | ?
`while` | ? | ? | ?
bool-expression | ? | ? | ?
`do..while` | ? | ? | ?
`for` | ? | ? | ?
iteration statement | ? | ? | ?
loop body | ? | ? | ?
loop | ? | ? | ?
execution | ? | ? | ?
execution jump | ? | ? | ?
`break` | ? | ? | ?
`continue` | ? | ? | ?
`Array` | ? | ? | ?
`int[]` | ? | ? | ?
Array Initialization | ? | ? | ?
Array Access for Assignment | ? | ? | ?
Array Access for Reading | ? | ? | ?
`Array.Resize` | ? | ? | ?
`Array.Length` | ? | ? | ?
`foreach` | ? | ? | ?
`2D-Array` | ? | ? | ?
2D-Array Initialization | ? | ? | ?
2D-Array Access for Assignment | ? | ? | ?
2D-Array Access for Reading | ? | ? | ?
Jagged Arrays | ? | ? | ?
Method | ? | ? | ?
`void` | ? | ? | ?
Return Type | ? | ? | ?
`()` | ? | ? | ?
Parameter | ? | ? | ?
Argument | ? | ? | ?
Parameter | ? | ? | ?
Parameter-List | ? | ? | ?
Named Arguments | ? | ? | ?
Optional Arguments | ? | ? | ?
Default Value | ? | ? | ?
`return` | ? | ? | ?
Code Paths | ? | ? | ?
Method Overloading | ? | ? | ?
Object-Oriented Programming | ? | ? | ?
Data | ? | ? | ?
Function | ? | ? | ?
Structured Programming | ? | ? | ?
Objects | ? | ? | ?
Instance Method | ? | ? | ?
Class | ? | ? | ?
Type | ? | ? | ?
`class` | ? | ? | ?
`new` | ? | ? | ?
Class Member | ? | ? | ?
Class Instance | ? | ? | ?
Garbage Collector | ? | ? | ?
`null` | ? | ? | ?
Invoke | ? | ? | ?
Field | ? | ? | ?
Static Class Member | ? | ? | ?
Static Class | ? | ? | ?
Global Access | ? | ? | ?
Constructor | ? | ? | ?
Initial Class Values | ? | ? | ?
Parameterless | ? | ? | ?
Default Contructor | ? | ? | ?
Finalizer | ? | ? | ?
Object Destruction | ? | ? | ?
`GC.Collect` | ? | ? | ?
Encapsulation | ? | ? | ?
Access Modifier | ? | ? | ?
`private` | ? | ? | ?
`protected` | ? | ? | ?
`public` | ? | ? | ?
`internal` | ? | ? | ?
Class Member Access | ? | ? | ?
Inheritance | ? | ? | ?
Property | ? | ? | ?
Getter Method | ? | ? | ?
Setter Method | ? | ? | ?
Validation | ? | ? | ?
Processing | ? | ? | ?
`get` | ? | ? | ?
`set` | ? | ? | ?
Expression Body Syntax | ? | ? | ?
Auto Property | ? | ? | ?
Read-Only Property | ? | ? | ?
Auto Property | ? | ? | ?
base-Class | ? | ? | ?
Inherit From | ? | ? | ?
Derived Class | ? | ? | ?
Child Class | ? | ? | ?
Parent Class | ? | ? | ?
`sealed` | ? | ? | ?
Polymorphism | ? | ? | ?
`as` | ? | ? | ?
`virtual` | ? | ? | ?
`override` | ? | ? | ?
`base` | ? | ? | ?
Abstraction | ? | ? | ?
`abstract` | ? | ? | ?
Implementation | ? | ? | ?
Composition | ? | ? | ?
"Composition over Inheritance" | ? | ? | ?
