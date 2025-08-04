# `maquereaux` $\LaTeX$ package 🐟

My personal LaTeX macros, with an emphasis on mathematical typesetting.

You will find a demo of all macros in `demo.pdf` (document in french, still WIP).

NB : the demo file use my custom class `atomathematyk` (mostly for using _IBM Plex_ as a font everywhere), you can get the class [here](https://github.com/LeoGuillon/atomathematyk), or just swap the document class to `article`.

## How to install

If you just wanna use it for a single project, you just have to copy `maquereaux.sty` at the root folder of the project, then call `\usepackage{maquereaux}`.

If you wanna use it for several projects, I strongly advise putting the package file in `~/texmf/tex/latex/` (on Linux/MacOS with TeXLive), so that it’s available everywhere.

## Commands development philosophy

As a (future) math teacher, the aim of these commands is to cover math domains learned at from middle school up to bachelor/master level.

When creating a command, I try to respect the following principles :

- write the command in english (so that it’s consistent with all other existing $\LaTeX$ commands) ;
- respect the mathematical conventions : if representing a set, the command should start with an uppercase letter ; otherwise, typically a function or operator, it should start with a lowercase letter ;
- a command representing a function or a common mathematical constant should write the function with roman (e.g. upright) font style ;
- of course, provide the best mathematical typesetting possible.
