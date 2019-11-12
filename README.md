# Cubed!

## Description
A 3D jumping game built with C++ and OpenGL, where you control a cube, avoiding lots of other polygonal obstacles. Press A and D to move left and right, and press space to jump. Score will be stored locally in a file called ```score.txt```.

## Requirements
```
g++ (with C++11 extension)
OpenGL, GL, GLU, GLUT (Newest version is OK, even though lots of the functions being used are deprecated. Forgot the exact version the program is made with.)
```

## Running
In Mac, compile the code with
```
g++ game.cpp -o game -framework OpenGL -framework GLUT
```
and then run the resulting ```game``` program, or you can change the output filename by giving the proper argument into the compiler. For Linux, compile the code using the command below.
```
g++ -I/usr/X11R6/include -L/usr/X11R6/lib -std=gnu++11 -lglut -lGLU -lGL -lXmu -lXext -lX11 -lm -o game game.cpp
```

## Author
Calvin Janitra Halim
