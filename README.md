Maze Generator
==============

A simple binary for generating mazes. When invoked, a maze is
generated and printed to standard out. To generate a maze, run:

    ./generate_maze

By default, a 10 cell by 10 cell maze is generated. You can pass in a
single, integer argument to change the size:

    ./generate_maze 20

Currently, only square mazes can be generated.

Example Output
--------------

    ./generate_maze
    +--+--+--+--+--+--+--+--+--+--+
       |     |        |  |     |  |
    +  +  +--+  +  +--+  +--+  +--+
    |           |     |  |        |
    +--+--+  +  +  +  +--+  +  +--+
    |     |  |                 |  |
    +--+  +  +--+--+--+--+--+  +  +
    |        |        |  |  |  |  |
    +--+  +  +  +  +  +--+--+  +  +
    |     |  |        |           |
    +  +  +  +  +--+--+  +--+  +  +
    |        |        |           |
    +--+--+--+  +  +  +  +  +--+  +
    |  |           |  |  |     |  |
    +--+--+  +  +  +  +  +  +--+  +
    |              |              |
    +--+  +  +  +--+  +--+  +  +  +
    |        |           |        |
    +  +  +  +--+  +  +  +  +  +  +
    |     |        |  |        |
    +--+--+--+--+--+--+--+--+--+--+
