# Computer Science: A Complete Guide

**This book is a work-in-progress. And should not be used as educational material.**

## Table of Contents
- [Computer Science: A Complete Guide](#computer-science-a-complete-guide)
  - [Table of Contents](#table-of-contents)
- [Part I - A Introduction to Computer Science](#part-i---a-introduction-to-computer-science)
  - [Getting Started](#getting-started)
    - [What is Computer Science](#what-is-computer-science)
    - [Why Study Computer Science](#why-study-computer-science)
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
- [Part II - Introduction to Computer Programming](#part-ii---introduction-to-computer-programming)
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
- [Part III - Programming Languages](#part-iii---programming-languages)
    - [JavaScript](#javascript)
    - [C++](#c)
    - [Python](#python)
    - [C](#c-1)
    - [Assembly Language](#assembly-language)
    - [Lisp](#lisp)
- [PART IV - The Developer Environment](#part-iv---the-developer-environment)
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
- [Part V - Fields in Computer Science](#part-v---fields-in-computer-science)
  - [Computer Networking](#computer-networking)
  - [The Web](#the-web)
    - [How the Internet Works](#how-the-internet-works)
    - [HTML](#html)
    - [CSS](#css)
    - [JavaScript on the Browser](#javascript-on-the-browser)
    - [ReactJS](#reactjs)
  - [Machine Learning w/ Python](#machine-learning-w-python)
- [Part VI - Writing Better Software](#part-vi---writing-better-software)
  - [Data Structures and Algorithms](#data-structures-and-algorithms)
  - [Design Patterns](#design-patterns)
- [Part VII - Mathematics for Computer Science](#part-vii---mathematics-for-computer-science)
- [Part VIII - Advanced Topics In Computer Science](#part-viii---advanced-topics-in-computer-science)
  - [AI, Machine Learning and Data Science](#ai-machine-learning-and-data-science)
  - [Computer Vision](#computer-vision)
  - [Algorithm Analysis](#algorithm-analysis)
- [Part IX - Applying Your Skills](#part-ix---applying-your-skills)
  - [Projects](#projects)
    - [Personal Projects](#personal-projects)
        - [Maintaining Your Project](#maintaining-your-project)
        - [Packaging Your Project](#packaging-your-project)
        - [Releasing Your Project](#releasing-your-project)
    - [Working With Open Source Projects](#working-with-open-source-projects)
      - [Finding Projects](#finding-projects)
    - [Working With Projects At Work](#working-with-projects-at-work)
    - [Startups](#startups)
  - [Work](#work)
- [Appendix](#appendix)
  - [Appendix A - Symbols](#appendix-a---symbols)
    - [Greek Alphabet](#greek-alphabet)
    - [Mathematical Symbols](#mathematical-symbols)
  - [Appendix B - A Big List Of Projects](#appendix-b---a-big-list-of-projects)
- [Solution Manual](#solution-manual)
  - [Exercises](#exercises-1)
  - [Projects](#projects-1)
  - [Research Questions](#research-questions)
- [Other](#other)

# Part I - A Introduction to Computer Science

## Getting Started

### What is Computer Science
### Why Study Computer Science

## The Field of Computer Science

## A Brief History of Computer Science

## Basics of Computing

# Part II - Introduction to Computer Programming

## Programming Basics

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

# Part III - Programming Languages

### JavaScript
### C++
### Python
### C
### Assembly Language
### End of Section

##### Research

1. Find a new language and create the equivalent of a "Hello, World" program in that language. Then, answer some of the following questions:
    - What style does this language use?
    - What are the benefits of using this language over the ones learned previously?
    - For what purpose was this language developed?

    A few unconventional languages to consider:
    - lisp
    - vimscript
    - ruby

# PART IV - The Developer Environment

### The Command Line
### Interlude: Buffers, Windows, Screens

### Make
### CMake
### Debugging
#### Print-Line Debugging
### Testing
### Logging

# Part V - Fields in Computer Science

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

# Part VI - Writing Better Software

## Data Structures and Algorithms
## Design Patterns

# Part VII - Mathematics for Computer Science

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

# Part VIII - Advanced Topics In Computer Science

## AI, Machine Learning and Data Science
## Computer Vision
## Algorithm Analysis

# Part IX - Applying Your Skills

## Projects

### Personal Projects

##### Maintaining Your Project
##### Packaging Your Project
##### Releasing Your Project

### Working With Open Source Projects

#### Finding Projects

### Working With Projects At Work

### Startups

## Work

Finding a Job
Building a Resume
Building a Portfolio
Marketing Yourself
On-the-Job Skills

# Appendix

## Appendix A - Symbols

### Greek Alphabet

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

### Mathematical Symbols

<table>
  <tr>
    <td>∈</td>
    <td>Element of</td>
  </tr>
  <tr>
    <td>∉</td>
    <td>Not an element of</td>
  </tr>
  <tr>
    <td>∀</td>
    <td>Universal Quantifier (For all)</td>
  </tr>
  <tr>
    <td>∃</td>
    <td>Existential Quantifier (There exists)</td>
  </tr>
  <tr>
    <td>⇒</</td>
    <td>If</td>
  </tr>
  <tr>
    <td>⇔</td>
    <td>If, and only if</td>
  </tr>
  <tr>
    <td>∴</td>
    <td>Therefore</td>
  </tr>
  <tr>
    <td>∵</td>
    <td>Because</td>
  </tr>
  <tr>
    <td>|</td>
    <td>Such that</td>
  </tr>
  <tr>
    <td>:</td>
    <td>Such that</td>
  </tr>
  <tr>
    <td>,</td>
    <td>Such that</td>
  </tr>
  <tr>
    <td>∫</td>
    <td>Integral</td>
  </tr>
  <tr>
    <td>d</td>
    <td>Derivative</td>
  </tr>
  <tr>
    <td>∂</td>
    <td>Partial Derivative</td>
  </tr>
  <tr>
    <td>∇</td>
    <td>Gradient</td>
  </tr>
  <tr>
    <td>lim</td>
    <td>Limit</td>
  </tr>
  <tr>
    <td>→</td>
    <td>Approaches</td>
  </tr>
  <tr>
    <td>∞</td>
    <td>Infinity</td>
  </tr>
  <tr>
    <td></td>
    <td>Vector</td>
  </tr>
</table>

## Appendix B - A Big List Of Projects

# Solution Manual

## Exercises
## Projects
## Research Questions

# Other

- Operating Systems
    - Unix-Like vs DOS
    - Windows
    - MacOS
    - Linux
    - BSD/Unix