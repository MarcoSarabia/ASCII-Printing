Lab Project: ASCII Printing
===================================
# Description
This project is a demonstration of ASCII art printing, implemented as part of a Computer Science course. The program, called `asciidraw`, allows users to print ASCII representations of various shapes and characters.

The project was originally outlined by Dr. Eric Freudenthal as part of the curriculum for CS 3320 Intro to Computer Architecture at The University of Texas at El Paso.

# Files
The following are source files for asciidraw
- uimain.c: Main file with the UI to interact with the user. Given the user input, it prints the desired shape.
- draw_shapes.c: Defines functions to draw simple shapes (e.g. square, triangle)
- draw_chars.c: Defines functions to draw characters.
- 11x16font.c: Defines bitmap array of 11x16 font (11 rows, 16 cols).  Each col is stored as a bitmap of type short
- draw.h: Header file containing all the declarations of the relevant methods used in this demo.

## Compilation Instructions
You can compile this program using the command

    $ cc  -g -O3 -o asciidraw uimain.c draw_shapes.c draw_chars.c 11x16font.c

The following command runs the program

    $ ./asciidraw

The following files are provided for your convenience (but not presently used)
- 5x7font.c: defines the bitmaps of a 5x7 font (5 rows, 7 cols).  Each col is stored as a bitmap of type char
- 8x12font.c: defines the bitmaps of an 8x12 font (8 rows, 12 cols).  Each row is stored as a bitmap of type char.


