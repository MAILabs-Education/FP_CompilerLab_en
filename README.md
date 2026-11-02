# FuncPro Homework: Implementing Functional Programming Language!

The goal of this homework is to invent your own functional programming language and develop an interpreter or compiler for it.

You can complete this laboratory work in a group of 2 or 3 people (or more - but this requires instructor's approval):

* 1-2 people - compiler/interpreter + example programs + brief documentation in README.md (you can replace this file with your own documentation)
* 2-3 people - compiler/interpreter + example programs + more detailed documentation on GitHub Pages
* 3 or more people - in addition to the above, may include the following:
  - IDE in browser
  - Jupyter Notebook support
  - Translation to JavaScript so the program can be executed in a browser
  - VS Code extensions

## Task

Your goal is to invent and implement your own functional programming language. Requirements:

* It should closely follow the functional programming paradigm, based on either [lambda calculus](https://en.wikipedia.org/wiki/Lambda_calculus) or [combinatory logic](https://en.wikipedia.org/wiki/Combinatory_logic).
* It should be more or less universal, i.e., implement recursion. Ideally - Turing-complete.
* At minimum, the language should allow you to program a function to calculate factorial.

> Keep in mind that writing parsers is a tedious task, so try to make the language syntax as simple as possible.

For inspiration:

* Learn [LISP](https://books.ifmo.ru/file/pdf/1918.pdf) - a programming language with very simple syntax.
* Combinatorial parsers and the [fparsec](https://www.quanttec.com/fparsec/) library if you want to implement a language with more complex syntax.
* [Top-Down Parser in F#](https://github.com/fholm/Vaughan).
* Interesting blog post about [parsing in F#](https://www.erikschierboom.com/2016/12/10/parsing-text-in-fsharp/).
* Parsing using [FsLex and FsYacc](https://realfiction.net/posts/lexing-and-parsing-in-f/) tools (not recommended).
* Implementation of [Scheme in F#](https://github.com/AshleyF/FScheme) - you can review this project for inspiration, but don't borrow code from it!

## Evaluation Criteria

* Project Statement: What makes your language or its implementation unique/interesting/excitement
* Universality (Turing Completeness)
* Sample programs (including factorial, but not limited to it)
* Originality and beauty of syntax
* Documentation
* Beauty of implementation

The preferred implementation language is F#.

In the documentation, explicitly list which language features you implemented:

* [ ] Named variables (`let`)
* [ ] Recursion
* [ ] Lazy evaluation
* [ ] Functions
* [ ] Closures
* [ ] Library functions: file input/output
* [ ] Lists / Sequences
* [ ] Library functions: lists/sequences

## Project Statement

An important part of the project is this project statement. Your goal is to invent a language and implement it in such a way that it would be original and exciting, making it different from standard tutorials on the internet, or the average implementation that a coding agent will create. Please describe why your project is interesting, how it differs from "average" implementation, and what are you especially proud of.

## Use of Generative AI

You may or may not chose to use generative AI for implementation of your programming language. If you chose to use generative AI, you need to explicitly describe the process of using it: which prompts you were using, which tests suites you developed and how, did you use side-by-side documentation, etc. Also, even when using generative AI, it is your responsibility to ensure that project code is purely functional. 

> Using generative AI without explicitly indicating so is a violation of academic principles.

## Repository

Please, fork this repository to your own GitHub and work on the project there. At the end of the project,
you need to submit the link together with the video (more info provided by your instructor).

## Phased Work

Since the project is quite large, it should be done in stages, uploading your code to GitHub at each stage:

* Stage 1: Development of abstract syntax tree and parser for your language + one sample program.
* Stage 2: Development of interpreter/compiler for your language.
* Stage 3: Writing example programs and documentation.

> Of course, you can change the language at later stages if you deem it necessary.

## Authors

Don't forget to mention your team in the README.md file, also indicating who did what. Also, the README.md file should include a brief guide to your language and some short code examples.

Name | Role in Project
------------------|---------------------
... | ...

