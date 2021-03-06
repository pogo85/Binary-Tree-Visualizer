Implementation of Bresenham's Circle and line drawing algorithms and
Tidy Drawings of Trees by Reingold and Tilford.

Libraries required: GLUT

Compile: g++ ./Tree-drawing/main.cpp -lglut -lGL -lGLU

Run: ./Tree-drawing/TreeVisualizer 
Documentation:
1. Documentation/Circleandlinedoxygen/html/index.html for bresenham's
circle and line drawing algorithm
2. Documentation/treedoxygen/html/index.html for tree drawing algorithm
3. Documentation/HTMLdocumentation/Documentation for general discussion,
timing analysis, references etc.

Circle and line drawing folder consists of 1 file: 1.
Circle\_linedrawing\_final.cpp: Draws a circle taking in input radius,
center coordinates and a line taking in end point coordinates

Tree drawing folder consists of 3 files: 1. bstfinal.h: Creates a simple
binary tree to be used for. Returns the root of the constructed tree to
main() 2. mainfinal.cpp: Does the implementation of Tidy Drawings and then
calls functions in draw.h for openGL display 3. drawfinal.h: draws the tree
using openGL. The nodes are drawn using Midpoint circle drawing and
lines using Bresenham's line drawing algorithm.
