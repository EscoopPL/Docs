# Escoop Syntax
Escoop's syntax is inspired by [Java](https://www.java.com) and [Python](https://www.python.org). The language requires static typing, and has mostly automatic type casting. For example, if you tried to input an integer into a function that requires a float, it would turn the integer into a float.
## Variable Declaration
To declare a variable, use Java syntax: <code><<span>type</span>> <<span>name</span>> = <<span>value</span>></code>
The primitive data types are:
int (64-bit signed integer, denoted by a number)
float (Double precision floating point value, denoted by a decimal point)
bool (Boolean value)
string (Array of chars, denoted by double quotes around a string)
char (Single unicode character, denoted by single quotes around a character)
## Class Declaration
As with Java, one class is stored in one file, but unlike Java, not everything is a class. In Escoop, there are 2 types of files. Runfiles, which have code to be ran, and class files, which contain a class. To declare a class in a file, after the identifier,  (see File Structure for more information) type <code>class <<span>class-name</span>> extends <<span>inherited-class</span>></code>. 
In Escoop, classes inherit other classes.