# Debugging Basics Workshop
Small workshop for sharing amongst Shendruk Lab on the fundamentals of debugging.
Quick start from here TODO

This is a series of exercises designed to introduce you to the basics of debugging.
These are based around using some variety of **visual** debugger, as opposed to a purely terminal based one.
Tutorials will be based off using the Visual Studio Code (VSC) debugging interface for convenenience but principles should also apply to other IDEs.

## Tim's notes
- Remove all python exercises except 5
- Make sure to cover:
    - C/ C++ debugging
    - Setting up necessary plugins for VSC (just basic one: pyland for python, c/c++ one too)
    - VSC - Config.json, using arguments (both python and C)
    - Breakpoints
    - Conditional breakpoints
    - Watch variables
    - Call stack
    - Try/ Catch/ Except
    - Testing(?) (At least Python `assert()`)
- Add solutions folder
- Set up actual notes, potentially in Jekyll?

## Folder Structure
```
DebuggingBasicsWorkshop
    .gitignore                  - Ignore file for git 
    README.md                   - Frontpage readme (this document)
    /Exercises                  - Contains example exercises
        ...
    /Solutions                  - Contains (a possible) solution to each exercise
        ...
```

## Credits
Compiled and written by Timofey Kozhukhov.
Exercises Ex1.py were taken from University of Edinburgh's Computer Modelling Course from the 2021 curriculum.
TODO: ask to be allowed to use these formally
