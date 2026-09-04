# Lab 1: "2-2 Excercises"

### Abstract

This repo is a clone of three text files that were examined for code errors.


### Resolved issues

`Text01.java`: File is fine as is. Added a helpful comment at the top

`Text02.java`: File was missing a semicolon on line 6. The `main()` method ended too early preventing the forth print statement from executing.

`Text03.java`: The `drawLegs()` method was written, but never called; had to add a line that called the method to print the missing parts. 

*Last one took me some time to understand because I was confused how `main()` was being called, but `drawLegs()` needed to be called. The way I understand it now is the java runtime starts at `main()` and it also starts other methods by calling them.*