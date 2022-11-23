C - Makefiles

In this project, I practiced writing Makefiles.
Tests heavy_check_mark

    tests: Folder of test files. Provided by Holberton School.

Helper Files raised_hands

    holberton.c: C function that displays a seahorse in text. Used for Makefile practice purposes throughout project. Provided by Holberton School.

    main.c: Main C function that runs the function defined in holberton.c. Provided by Holberton School.

Header File file_folder

    m.h: Header file defining the function prototype used in holberton.c. Provided by Holberton School.

Tasks page_with_curl

    0. make -f 0-Makefile
        0-Makefile: Makefile that creates an executable holberton based on holberton.c and main.c. Includes:
            Rule all that builds the executable.

    1. make -f 1-Makefile
        1-Makefile: Makefile that creates an executable holberton based on holberton.c and main.c. Builds on 0-Makefile with:
            Variable CC that defines the compiler to be used.
            Variable SRC that defines the .c files to compile.
            The all rule only recompiles updated source files.

