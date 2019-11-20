# Best Practices Checklist

## Table of Contents

- [What is this?](#what-is-this)
- [Why this repo?](#why-this-repo)
- [What counts as an acceptable entry?](#what-counts-as-an-acceptable-entry)
- [Language Specific Resources](#language-specific-resources)
  - [ALGOL Language Family](#algol-language-family)
    - [Dart](#dart)
  - [C Language Family](#c-language-family)
    - [C++](#C++)
    - [D](#d)
    - [Go](#go)
    - [Python](#python)
    - [Nim](#nim)
    - [Ruby](#ruby)
    - [Rust](#rust)
  - [Java Language Family](#java-language-family)
    - [Java](#java)
    - [Scala](#scala)
  - [JavaScript Language Family](#javascript-language-family)
    - [JavaScript](#javascript)
  - [Prolog Language Family](#prolog-language-family)
    - [Elixir](#elixir)
    - [Erlang](#erlang)
  - [Lisp Language Family](#lisp-language-family)
    - [Clojure](#clojure)
    - [Common Lisp](#common-lisp)
  - [ML Language Family](#ml-language-family)
    - [OCaml](#ocaml)
  - [Unnown Language Family](#unnown-language-family)
    - [Pony](#pony)
    - [General API Design and Tooling](#general-api-design-and-tooling)

## What is this

This is a collection of language specific resources that can be used to look up the best practices followed by a particular language's community.

## Why this repo

I am a programming language enthusiast and I like picking up new languages all the time. Like most curious devs I learn different languages by implementing some side projects using them. This can be achieved by writing quick hacks that mostly turn out to be ugly code but if we want our projects to be publicly available to be used or hacked on by others we must ensure that the code we write is idiomatic and easily understood.

The purpose of this repo is to serve as a collection of resources that one can quickly look up while building such projects to make sure that their code is idiomatic before they make it public.

## What counts as an acceptable entry

It could be anything from articles to books to videos that describes:

- how to write idiomatic code in a particular language
- what build systems / package managers to use and the best practices surrounding these aforementioned tools
- how to good write unit/integration tests
- different styles and idioms of a language
- software design in general etc
- new language section (if you find that the resources for your favourite language are missing feel free to create a new section and add them)

**Note:** If you are adding a book to the list make sure that it is a free ebook. Amazon links to buy books will not be accepted.

## Language Specific Resources

### Language Families

### ALGOL Language Family

#### Dart

- [Dart Language Tour](https://dart.dev/guides/language/language-tour)

### C Language Family

#### C++

- [Google C++ Style Guide](https://google.github.io/styleguide/cppguide.html)
- [ISO C++ Core Guidelines](http://isocpp.github.io/CppCoreGuidelines/CppCoreGuidelines)

#### D

- [Pragmatic D Tutorial: Idiomatic D](https://qznc.github.io/d-tut/idiomatic.html)
- [The D Style](https://dlang.org/dstyle.html)

#### Go

- [Clean Go](https://github.com/Pungyeon/clean-go-article)
- [Domain Driven Design in Go](https://github.com/marcusolsson/goddd)
- [Effective Go](https://golang.org/doc/effective_go.html)
- [How to Write Go Code](https://golang.org/doc/code.html)
- [Learn Go With Tests](https://quii.gitbook.io/learn-go-with-tests/)
- [The Uber Go Style Guide](https://github.com/uber-go/guide)

#### Python

- [Design Patterns Implementations](https://github.com/faif/python-patterns)
- [Design Patterns Toptal Blog Post](https://www.toptal.com/python/python-design-patterns)
- [Google Python Style Guide](https://google.github.io/styleguide/pyguide.html)
- [Hitchhiker's Guide to Python](https://docs.python-guide.org/)
- [PEP8](https://www.python.org/dev/peps/pep-0008/)
- [Python API Checklist](https://github.com/vintasoftware/python-api-checklist)

#### Nim

- [Nim Notes](https://scripter.co/notes/nim)
- [Nim Style Guide](https://nim-lang.org/docs/nep1.html)

#### Ruby

- [Best Ruby](http://franzejr.github.io/best-ruby/)
- [Let’s Read! — Eloquent Ruby](https://medium.com/@baweaver/lets-read-eloquent-ruby-ch-1-b2115d1416a6)
- [RSpec Best Practices](https://github.com/abinoda/rspec-best-practices)
- [Ruby Style Guide](https://rubystyle.guide/)

#### Rust

- [3 Day Rust Course by Ferrous Systems](https://ferrous-systems.github.io/rust-three-days-course)
- [Cargo Guide](https://doc.rust-lang.org/cargo/guide/)
- [Elements of Rust](https://github.com/ferrous-systems/elements-of-rust)
- [Rust By Example](https://doc.rust-lang.org/rust-by-example/macros/overload.html)
- [Rust Cookbook](https://rust-lang-nursery.github.io/rust-cookbook/)
- [Rust Language Cheat Sheet](https://cheats.rs/)
- [Rust Language Reference](https://doc.rust-lang.org/nightly/reference/introduction.html)
- [Rust Programming Language (Book)](https://doc.rust-lang.org/book/)

### Java Language Family

#### Java

- [Google Java Style Guide](https://google.github.io/styleguide/javaguide.html)
- [Java Code Conventions](https://www.oracle.com/technetwork/java/codeconventions-150003.pdf)
- [Principles of Lean Java](http://www.ameyalokare.com/software/2018/01/13/lean-java-principles.html)

#### Scala

- [Scala Best Practice Idioms](https://alvinalexander.com/scala/scala-best-practices-idioms-cookbook)
- [Scala Idioms](https://leanpub.com/scalaidioms/read)
- [Scala School](https://twitter.github.io/scala_school/)

### JavaScript Language Family

#### Javascript

- [Design Patterns Implementations](https://github.com/faif/python-patterns)
- [Design Patterns Toptal Blog Post](https://www.toptal.com/python/python-design-patterns)
- [Eloquent Javascript](http://eloquentjavascript.net/)
- [Google JavaScript Style Guide](https://google.github.io/styleguide/jsguide.html)
- [Hitchhiker's Guide to Python](https://docs.python-guide.org/)
- [JS: The Right Way](https://jstherightway.org/)
- [PEP8](https://www.python.org/dev/peps/pep-0008/)
- [Python API Checklist](https://github.com/vintasoftware/python-api-checklist)
- [wemake-python-styleguide (contains a list of stylistic rules / guidelines for Python code)](https://wemake-python-stylegui.de/en/latest/pages/usage/violations/index.html)
- [You Don't Know JS](https://github.com/getify/You-Dont-Know-JS)

### Prolog Language Family

#### Elixir

- [Credo's Elixir Style Guide](https://github.com/rrrene/elixir-style-guide)

#### Erlang

- [Spawned Shelter](http://spawnedshelter.com)

### Lisp Language Family

#### Clojure

- [Clojure Style Guide](https://github.com/bbatsov/clojure-style-guide)

#### Common Lisp

- [Standard CL Symbols](https://www.hexstreamsoft.com/articles/notes-tips-standard-common-lisp-symbols/)

### ML Language Family

#### OCaml

- [OCaml Style Guide](https://github.com/lindig/ocaml-style)

### Unnown Language Family

#### Pony

- [Pony Patterns](https://patterns.ponylang.io/)

#### General API Design and Tooling

- [Designing unix tools](https://monkey.org/~marius/unix-tools-hints.html)
