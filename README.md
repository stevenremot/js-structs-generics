#structs-generics#

This is a simple experiment to implement in javascript a statically typed
structure semantic, and a generic function system with different implementations
depending on the type of the arguments.

The goal is not to create a production-ready library, but to experiment a little
bit javascript's semantic power. Today, the javascript community seems focused
on using it to implement new languages that run on the top of javascript. Here,
I want to use javascript's power to create new semantic for the language, like
Lisp programmers often do.

This code has been written in a kind of literate programming, using Emacs' Org
mode. You can find the source and the documentation in the file
`structs-generics.org`. You can tangle it to generate the actual code using the
command `org-babel-tangle`, or by pressing `C-c C-v t` when visiting the org
file.

If you don't want to use Emacs, you still can read the file with any other text
editor. You can generate the source using the command :

```sh
    emacs -Q --batch --eval "(progn (require 'ob-tangle)(org-babel-tangle-file \"struct-method.org\"))"
