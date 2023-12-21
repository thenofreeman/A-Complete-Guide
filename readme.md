# Computer Science: A Complete Guide

**This book is a complete work-in-progress. And should not be used as educational material.**

## Table of Contents
- [Computer Science: A Complete Guide](#computer-science-a-complete-guide)
  - [Table of Contents](#table-of-contents)
  - [Preface](#preface)
  - [About the Authors](#about-the-authors)
- [Part I - A Introduction to Computer Science](#part-i---a-introduction-to-computer-science)
  - [Getting Started](#getting-started)
    - [What is Computer Science](#what-is-computer-science)
    - [Why Study Computer Science](#why-study-computer-science)
    - [What This Book Is About](#what-this-book-is-about)
    - [What This Book Is NOT About](#what-this-book-is-not-about)
    - [Motivation For Writing This Book](#motivation-for-writing-this-book)
    - [Who This Book Is For](#who-this-book-is-for)
    - [How To Read This Book](#how-to-read-this-book)
        - [Exercises, Projects and Research](#exercises-projects-and-research)
        - [Style and Notation](#style-and-notation)
  - [The Field of Computer Science](#the-field-of-computer-science)
  - [A Brief History of Computer Science](#a-brief-history-of-computer-science)
  - [Basics of Computing](#basics-of-computing)
    - [Number Systems](#number-systems)
        - [Number Systems](#number-systems-1)
        - [Decimal](#decimal)
        - [Binary](#binary)
        - [Hexadecimal](#hexadecimal)
        - [Conversions](#conversions)
        - [Number System Indicators](#number-system-indicators)
      - [Exercises](#exercises)
      - [Research](#research)
- [Part II - Computer Programming](#part-ii---computer-programming)
  - [Programming Basics](#programming-basics)
    - ["Hello, World!"](#hello-world)
        - ["Hello, World!" Examples](#hello-world-examples)
    - [Variables](#variables)
        - [Scope](#scope)
    - [Data Types](#data-types)
        - [Integers](#integers)
        - [Floating Point](#floating-point)
        - [Characters](#characters)
        - [Strings](#strings)
        - [Arrays](#arrays)
        - [Memory Address](#memory-address)
        - [Objects](#objects)
        - [Other Types](#other-types)
    - [Control Flow Statements](#control-flow-statements)
        - [if](#if)
        - [if-else](#if-else)
        - [switch](#switch)
    - [Loops](#loops)
        - [while](#while)
        - [for](#for)
        - [for-each](#for-each)
    - [Functions](#functions)
    - [Picking a Language](#picking-a-language)
      - [Programming Styles](#programming-styles)
    - [Editors and IDEs](#editors-and-ides)
    - [Compilers and Interpreters](#compilers-and-interpreters)
  - [Programming Languages](#programming-languages)
    - [JavaScript](#javascript)
    - [C++](#c)
    - [Python](#python)
    - [C](#c-1)
    - [Assembly Language](#assembly-language)
  - [Developer Environment](#developer-environment)
    - [The Command Line](#the-command-line)
    - [Interlude: Buffers, Windows, Screens](#interlude-buffers-windows-screens)
    - [Vim](#vim)
        - [What is Vim?](#what-is-vim)
        - [Why use Vim?](#why-use-vim)
        - [The General Idea](#the-general-idea)
        - [Getting Started](#getting-started-1)
        - [Moving around](#moving-around)
        - [Editing Text](#editing-text)
        - [Selecting Text](#selecting-text)
        - [Other Common Editor Tasks](#other-common-editor-tasks)
        - [Combining Commands](#combining-commands)
        - [Closing](#closing)
        - [More Resources](#more-resources)
    - [Vim, Continued](#vim-continued)
        - [Searching](#searching)
    - [Emacs](#emacs)
    - [Git](#git)
        - [What is Git?](#what-is-git)
        - [Why use Git?](#why-use-git)
        - [Git and GitHub?](#git-and-github)
        - [Branches](#branches)
        - [Next Steps](#next-steps)
        - [More Resources](#more-resources-1)
        - [Unorganized Commands](#unorganized-commands)
    - [Make](#make)
    - [CMake](#cmake)
    - [Debugging](#debugging)
      - [Print-Line Debugging](#print-line-debugging)
    - [Testing](#testing)
    - [Logging](#logging)
  - [Computer Networking](#computer-networking)
  - [The Web](#the-web)
    - [How the Internet Works](#how-the-internet-works)
    - [HTML](#html)
    - [CSS](#css)
    - [JavaScript on the Browser](#javascript-on-the-browser)
    - [ReactJS](#reactjs)
  - [Machine Learning w/ Python](#machine-learning-w-python)
  - [Data Structures and Algorithms](#data-structures-and-algorithms)
  - [Design Patterns](#design-patterns)
  - [Mathematics for Computer Science](#mathematics-for-computer-science)
- [Part XX - Advanced Topic In Computer Science](#part-xx---advanced-topic-in-computer-science)
  - [AI, Machine Learning and Data Science](#ai-machine-learning-and-data-science)
  - [Computer Vision](#computer-vision)
  - [Algorithm Analysis](#algorithm-analysis)
  - [Projects](#projects)
  - [Work](#work)
  - [Appendix](#appendix)
    - [Symbols](#symbols)
        - [Greek Alphabet](#greek-alphabet)
  - [Other](#other)

## Preface
## About the Authors
# Part I - A Introduction to Computer Science
## Getting Started
### What is Computer Science
### Why Study Computer Science
### What This Book Is About
### What This Book Is NOT About
### Motivation For Writing This Book
### Who This Book Is For
### How To Read This Book
##### Exercises, Projects and Research

Following every section, you will find some combination of sub-sections titled Exercises, Projects and/or Research. These sections are to test yourself and interact with the material more deeply. They can be used as follows:
- Exercises: Like any textbook these are your traditional exercises or problem sets. They are labeled with varying difficulty and will generally have a well-defined answer or at least one that can be found by reading this book. Some exercises will take longer than others to complete, but an advanced student shouldn't find themselves spending too much time to come up with an adequate answer at least. Solutions* to exercises are listed on the book's website. (Not all solutions are definite, or the only possible answers.)
- Projects: Longer and more in-depth than the exercises, Projects will generally take a reader a considerable amount of time to complete. They are generally left open-ended to let your imagination turn them into whatever you like, but some are labeled either solved or verifiable. Projects labeled solved have source code listed on the book's website, while verifiable projects mean you can upload your solution on the book's website to be tested for completeness.
- Research: Questions in this section follow a similar pattern to "Exercises" except they are completely open-ended, and you are almost guaranteed not to be able to find an answer in this book (at least at that point in reading). This is your opportunity to practice a Computer Scientist's greatest skill: research. 

##### Style and Notation

`C-x` means CONTROL+x (or possibly COMMAND+x on MacOS)
`M-x` means ALT+x. (or possibly COMMAND+x on MacOS)

With commands and other _, things wrapped in:
- square brackets, `[...]`, are optional.
- chevrons, `<...>`, are required, but variable.

All other text is meant to be verbatim, unless otherwise obvious (such as personalized strings).

## The Field of Computer Science

## A Brief History of Computer Science

## Basics of Computing

### Number Systems

<div style="border: 1px solid grey; border-radius: 8px; padding: 0 1.5em">

##### Number Systems

Number systems are ...

##### Decimal
##### Binary
##### Hexadecimal
##### Conversions
##### Number System Indicators
- `0x1`
- `0b1`
- `01`
#### Exercises
1. Express the decimal number 245 in Binary, and Hexadecimal.
2. Another common number system is Octal -- base 8. Write the following characters in Octal:
    - 4
    - 9
    - 256
    - 2027
#### Research
1. Find another number system apart from the ones mentioned in this section and try to answer the following questions: 
    - What characters are used to represent its values? 
    - What are the use cases for it? 
2. As explained, most of the common number systems have indicators to distinguish them from numbers of other systems, how is Octal represented in this manner?

</div>

# Part II - Computer Programming

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

```
if CONDITION:
  // do something
else 
  // do something
```

```
if CONDITION:
  // do something
else if CONDITION:
  // do something
else 
  // do something
```

##### switch

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

## Programming Languages

### JavaScript
### C++
### Python
### C
### Assembly Language

## Developer Environment

### The Command Line
### Interlude: Buffers, Windows, Screens

### Vim

<div style="border: 1px solid grey; border-radius: 8px; padding: 0 1.5em">

##### What is Vim?

Vim is a powerful text editor and key binding set for working with text files. It has been around since the 1970s and is widely used by developers and hobbyist to date.

##### Why use Vim?

- Speed and Efficiency
- Reduced RSI
- Powerful Tool-set
- Vim can be emulated in just about every editor, whether via a plugin or built-in feature, so you can take your skills wherever they lead you.

Essentially, if there is some task you wish to do within a file: Vim can do it, and likely more efficiently than other editors or tools available.

##### The General Idea

Commands...
Modes

##### Getting Started

From the command line run: `vim [filename]`, or open the app on your desktop, if it exists.

After making changes, you can save and quit by typing `:wq` followed by the ENTER key. To save without quitting use just `:w`, or to quit without saving type `:q`. If you are unable to quit because you have unsaved changes that you don't want to save, use `:q!` to quit and discard those changes.

##### Moving around

Move your cursor with `h`, `j`, `k`, `l`. They correspond with movement to the LEFT, DOWN, UP, and RIGHT, respectively. This is the hardest but most crucial command-set to learning Vim. Spend a good amount of time here before moving on.

Notice how when you cross vertically over a shorter line (between two longer lines) that Vim remembers the horizontal position you were at before moving.

Move around by words (groups of characters) with `w`, `b`, `e`. 

- `w` moves the cursor forward by the beginning of words, 
- `b` moves the cursor backwards by the beginning of words, and 
- `e` moves forward by the end of words. 

Each of these commands have a capital-case counter-part (`W`, `B`, `E`) that essentially do the same command except they are strictly whitespace delimited.

Within a line, you can jump to the beginning or end of it with `0` and `$`, respectively. Alternatively, if you want to go to the first non-whitespace character in the line, use `^` instead of `0`.

You can quickly jump to the top or the bottom of a file:

- `gg` to go to the top, and
- `G` to jump to the bottom.

`C-f` and `C-b` allow you to move forward and backward in the file by a full screen height. Also, `C-d` and `C-u` are useful, moving up or down by a half screen height.

If at anytime you entered the wrong movement command, or for any other reason, you want to get back to where you just were a moment ago: `C-o` will take you back to your last position. If you continue to hit `C-o` it will take you back more, through your positional history in the file.

##### Editing Text

So we can move around, but what use is an editor without editing. To begin typing text we have to enter `INSERT` mode

`i` and `a`, and their counterparts `I` and `A`, put your cursor into `INSERT`.
- `i` before the cursor,
- `a` after the cursor,
- `I` at the beginning of the line (ie. `^i`), and 
- `A` at the end of the line.

Also, `o` and `O` are useful for entering `INSERT` mode by opening a new line below or above the current line.

Commands like `dd` delete the complete current line; `C` deletes the current line AFTER the cursor and enters insert mode.

##### Selecting Text

##### Other Common Editor Tasks

`y y` `p`

`u` `C-r`

##### Combining Commands

We've encountered a few command combinations in our brief tour so far: `gg` and `dd`.

`d w` `d j`

`S-v j d` `S-v y j p`

##### Closing

See the cheatsheet in [More Resources](#more-resources) for a full list of available commands. But note: what you can do with Vim far extends the commands listed in the list below, it is the way in which you combine them, extend them, and introduce plug-ins that truly make Vim an every-thing tool.

If still have a taste for what Vim can offer, the next section goes into more use cases and utilities within Vim.

##### More Resources

</div>

### Vim, Continued

<div style="border: 1px solid grey; border-radius: 8px; padding: 0 1.5em">

##### Searching

</div>

### Emacs
### Git

<div style="border: 1px solid grey; border-radius: 8px; padding: 0 1.5em">

##### What is Git?

##### Why use Git?

##### Git and GitHub?

##### Branches

##### Next Steps

##### More Resources

##### Unorganized Commands

- `git init`
- `git clone [url]`
- `git remote add origin [url]`
- `git add [files]`
- `git commit -m "your message message"`
- `git push [-u] origin master`
- `git push`
- `git status`
- `git ls-files`
- `git log`
- `alias loga='git log --graph --pretty=format:'\''%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset'\'' --abbrev-commit'`

.gitignore

</div>

### Make
### CMake
### Debugging
#### Print-Line Debugging
### Testing
### Logging

## Computer Networking
## The Web
### How the Internet Works
### HTML
### CSS
### JavaScript on the Browser
### ReactJS
## Machine Learning w/ Python
Scikit-learn
Pandas
...

## Data Structures and Algorithms
## Design Patterns
## Mathematics for Computer Science
College Algebra and Pre-Calculus
Discrete Mathematics
Linear Algebra
Calculus
- What is Calculus
- Limits
- The Derivative
- Integrals
- Partial Derivatives
- Gradient
- Derivative Tests
Probability
Statistics
# Part XX - Advanced Topic In Computer Science
## AI, Machine Learning and Data Science
## Computer Vision
## Algorithm Analysis
## Projects
- Starting Project
- Maintaining Projects
- Finding Projects
- Packaging Projects
- Releasing Projects
- Suggested Projects
## Work
Finding a Job
Building a Resume
Building a Portfolio
Marketing Yourself
On-the-Job Skills
## Appendix
### Symbols

##### Greek Alphabet

<table>
  <tr>
    <td>Alpha</td>
    <td>Α</td>
    <td>α</td>
  </tr>
  <tr>
    <td>Beta</td>
    <td>Β</td>
    <td>β</td>
  </tr>
  <tr>
    <td>Gamma</td>
    <td>Γ</td>
    <td>γ</td>
  </tr>
  <tr>
    <td>Delta</td>
    <td>Δ</td>
    <td>δ</td>
  </tr>
  <tr>
    <td>Epsilon</td>
    <td>Ε</td>
    <td>ε</td>
  </tr>
  <tr>
    <td>Zeta</td>
    <td>Ζ</td>
    <td>ζ</td>
  </tr>
  <tr>
    <td>Eta</td>
    <td>Η</td>
    <td>η</td>
  </tr>
  <tr>
    <td>Theta</td>
    <td>Θ</td>
    <td>θ</td>
  </tr>
  <tr>
    <td>Iota</td>
    <td>Ι</td>
    <td>ι</td>
  </tr>
  <tr>
    <td>Kappa</td>
    <td>Κ</td>
    <td>κ</td>
  </tr>
  <tr>
    <td>Lambda</td>
    <td>Λ</td>
    <td>λ</td>
  </tr>
  <tr>
    <td>Mu</td>
    <td>Μ</td>
    <td>μ</td>
  </tr>
  <tr>
    <td>Nu</td>
    <td>Ν</td>
    <td>ν</td>
  </tr>
  <tr>
    <td>Xi</td>
    <td>Ξ</td>
    <td>ξ</td>
  </tr>
  <tr>
    <td>Omicron</td>
    <td>Ο</td>
    <td>ο</td>
  </tr>
  <tr>
    <td>Pi</td>
    <td>Π</td>
    <td>π</td>
  </tr>
  <tr>
    <td>Rho</td>
    <td>Ρ</td>
    <td>ρ</td>
  </tr>
  <tr>
    <td>Sigma</td>
    <td>Σ</td>
    <td>σ</td>
    <td>ς</td>
  </tr>
  <tr>
    <td>Tao</td>
    <td>Τ</td>
    <td>τ</td>
  </tr>
  <tr>
    <td>Upsilon</td>
    <td>Υ</td>
    <td>υ</td>
  </tr>
  <tr>
    <td>Phi</td>
    <td>Φ</td>
    <td>φ</td>
  </tr>
  <tr>
    <td>Chi</td>
    <td>Χ</td>
    <td>χ</td>
  </tr>
  <tr>
    <td>Psi</td>
    <td>Ψ</td>
    <td>ψ</td>
  </tr>
  <tr>
    <td>Omega</td>
    <td>Ω</td>
    <td>ω</td>
  </tr>
</table>

Maths Symbols
## Other
- Operating Systems
    - Unix-Like vs DOS
    - Windows
    - MacOS
    - Linux
    - BSD/Unix