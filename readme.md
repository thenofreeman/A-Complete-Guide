# Computer Science: A Complete Guide

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
  - [Introduction to Programming](#introduction-to-programming)
    - [Basic Concepts](#basic-concepts)
      - ["Hello, World!"](#hello-world)
      - [Variables](#variables)
      - [Data Types](#data-types)
      - [Control Flow Statements](#control-flow-statements)
      - [Loops](#loops)
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

## Introduction to Programming

### Basic Concepts

#### "Hello, World!"
#### Variables
#### Data Types
#### Control Flow Statements
#### Loops
#### Functions

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
Greek Alphabet
Maths Symbols
## Other
- Operating Systems
    - Unix-Like vs DOS
    - Windows
    - MacOS
    - Linux
    - BSD/Unix