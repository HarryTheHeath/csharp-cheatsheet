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
Variable Scope | The reacha & validity of a variable | { This.variableScope } | [Variables](https://github.com/forsbergsskola-se/gp21-21-0927-csharp-basics-nim-HarryTheHeath/blob/main/assignments/003.3.1-console-basics-1.md#3---variables)
`int` | Integer: whole numbers | `postive: 1, negative : -1` | [Basic Data Types](https://github.com/forsbergsskola-se/gp21-21-0927-csharp-basics-nim-HarryTheHeath/blob/main/slides/003.3.1-console-basics-1.md#4-basic-data-types)
`float` | Fractional numbers + f (floating point numericals) | `0.25f` | [Basic Data Types](https://github.com/forsbergsskola-se/gp21-21-0927-csharp-basics-nim-HarryTheHeath/blob/main/slides/003.3.1-console-basics-1.md#4-basic-data-types)
`double` | Less accurate than float, but better performance & fractionals | `double a = 12.3; double bacteriaSize = 24e-10;` | [Basic Data Types](https://github.com/forsbergsskola-se/gp21-21-0927-csharp-basics-nim-HarryTheHeath/blob/main/slides/003.3.1-console-basics-1.md#4-basic-data-types)
`bool` | True or false literal flags | `bool check = true; bool isWinning = false;` | [Basic Data Types](https://github.com/forsbergsskola-se/gp21-21-0927-csharp-basics-nim-HarryTheHeath/blob/main/slides/003.3.1-console-basics-1.md#4-basic-data-types)
`char` | Uses unicode for single characters | `char euroSign = "€"; foreach(char c in helloWorld) {}` | [Basic Data Types](https://github.com/forsbergsskola-se/gp21-21-0927-csharp-basics-nim-HarryTheHeath/blob/main/slides/003.3.1-console-basics-1.md#4-basic-data-types)
`string` | ? | ? | ?
`byte` | ? | ? | ?
Implicit Casting | ? | ? | ?
Explicit Casting | ? | ? | ?
Type Conversion | ? | ? | ?
`Convert.ToInt32` | ? | ? | ?
Operators | ? | ? | ?
Arithmetic Operators | ? | ? | ?
`+` | ? | ? | ?
`-` | ? | ? | ?
`*` | ? | ? | ?
`/` | ? | ? | ?
`%` | ? | ? | ?
`+=` | ? | ? | ?
`-=` | ? | ? | ?
`++` | ? | ? | ?
`--` | ? | ? | ?
Post-Increment `i++` | ? | ? | ?
Pre-Increment `++i` | ? | ? | ?
`System.Math` | ? | ? | ?
`static` | ? | ? | ?
`Math.Max` | ? | ? | ?
`Math.Min` | ? | ? | ?
`Math.Sqrt` | ? | ? | ?
`Math.Abs` | ? | ? | ?
`Math.Round` | ? | ? | ?
`Math.Floor` | ? | ? | ?
`Math.Ceiling` | ? | ? | ?
`Math.Clamp` | ? | ? | ?
`Math.Pow` | ? | ? | ?
`string.Length` | ? | ? | ?
`string.ToUpper` | ? | ? | ?
`string.+` | ? | ? | ?
`$"{}"` | ? | ? | ?
`string.[]` | ? | ? | ?
`string.IndexOf` | ? | ? | ?
`string.SubString(int)` | ? | ? | ?
`string.Substring(int, int)` | ? | ? | ?
`string.Replace` | ? | ? | ?
immutable | ? | ? | ?
Logical Operators | ? | ? | ?
`!` | ? | ? | ?
`&&` | ? | ? | ?
`||` | ? | ? | ?
Comparison Operators | ? | ? | ?
`>` | ? | ? | ?
`==` | ? | ? | ?
`!=` | ? | ? | ?
`||` | ? | ? | ?
`>=` | ? | ? | ?
`<=` | ? | ? | ?
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
