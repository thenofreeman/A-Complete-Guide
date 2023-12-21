## Programming Basics

### "Hello, World!"

A "Hello, World!" program is generally the bare-minimum code you need to run for in a language to test if everything is configured properly so that you may begin writing more elaborate programs. 

They generally output some text and optionally get some input from the user.

"Hello, World!" is a notational convention that dates back to the 1970s with the C programming language.

##### "Hello, World!" Examples

Below are a few examples of "Hello, World!" programs in various languages. Examples are introduced in order of appearance in this book, followed by a few other examples in alphabetical order. 

Explanations of each language's "Hello, World!" are explained in more detail when the particular language is formally introduced.

Pseudocode

```
print "Hello, World!"
```

C++

```
#include <iostream>

// This is a comment!

int main()
{
  std::cout << "Hello, World!" << std::endl;

  return 0;
}
```

Java

```
// This is a comment!

class Main {
  public static void main(String[] args) {
      System.out.println("Hello, World!");
  }
}
```

JavaScript

```
// This is a comment!

console.log('Hello, World!)
```

Python

```
# This is a comment!

print("Hello, World!")
```

C

```
#include <stdio.h>

int main() {
  printf("Hello, World!);

  return 0;
}
```

### Variables

##### Scope

### Data Types

##### Integers

```
42
```

##### Floating Point

```
3.14159
```

##### Characters

```
'z'
```

##### Strings

```
"This is a string"
```

In a nutshell, strings are just lists of characters in a convenient structure (lists more precisely next section). Some languages define them as Objects, and some as primitive types.

Strings are usually enclosed with double quotes, eg. `"some string"`, but many languages don't strongly distinguish between double (`"`) and single (`'`) quotes. Some languages -- such as JavaScript -- also use back-ticks (`` ` ``) to represent string. 

FYI: The name `string` comes from the idea of "star-ing" characters. This will make more sense soon, but it basically comes down a data type of `char*` denoting a list of character, ie string.

##### Arrays

Arrays, or Lists, are ...

##### Memory Address
##### Objects
##### Other Types

Function
Symbol

### Control Flow Statements

##### if

```
if CONDITION:
  // do something
```

##### if-else

An `else` can be appended to a if-statement as a catch-all for to be run when the if condition is not met.

```
if CONDITION:
  // do something if true
else:
  // do something if false
```

If you want more statements before the catch-all `else`, add `else if` statements with their own conditions.

```
if CONDITION:
  // do something if true
else if CONDITION:
  // do something if the first condition is false
  // but the second condition is true
else:
  // do something if all conditions are false
```

You can arbitrarily add more `else if` conditions as needed, but an if statement can only have one `if` condition and one `else`.

##### switch

As you can see, chaining if-else-ifs can become a mess. The switch statement was invented to clear up this headache.

```
switch VALUE:
  case OPTION-1:
    // do something
  case OPTION-2:
    // do something
  case OPTION-3:
    // do something
  default:
    // do something
```

### Loops

Loops are like Control Flow Statements except the statements in their body are repeated until the condition is false.

##### while

```
while CONDITION:
  // do something
```

##### for

```
for COUNTER = 0...10
  // do something with COUNTER variable
```

##### for-each

Some languages also define for-each loops that behave like for-loops except instead of incrementing a counter they iterate through some container like a List or Object.

```
foreach ITEM in LIST:
  // do something with ITEM value
```

### Functions

### Picking a Language
#### Programming Styles

OOP/Functional
Procedural/...
Language Styles
- C-style
- Lisp
- pythonic?

Indentation, Spacing and Newlines
Nesting
Case
- camelCase
- PascalCase
- snake_case
- kebab-case
- CONST_CASE
- ccase

### Editors and IDEs

VSCode
JetBrains Suite
Advanced Editors (see sections below)

### Compilers and Interpreters
