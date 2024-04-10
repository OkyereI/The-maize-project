# Maze_project
A simple Ray Casting 3D engine using SDL as the rendering back-end.

# <u>AUTHORS</u>
- Isaac Okyere ... [github](https://github.com/OkyereI/)
This is a sole project for Simple Ray Casting 3D   Engine using SDL

## This project is part of the alx project for students to develop to improve their skills acquire for game development in C
## Keyboard Keys for Players DIR
- `Arrow Keys` -- Player Directions 
- `R` -- Refresh 
- `M` -- Map 
- `C` -- Zoom Player view 
- `[` -- Zoom Out in Game 
- `]` -- Zoom In in Game 
- `F` -- Change Views (Normal view to Panoramic view and vice versa) 
- `T` -- Change Texture of walls and square columns 

### <u>Tools and Languages Used...</u>
- C language
- SDL2 (Simple Directmedia Layer)
- Ray-Casting
- Bash

Compiling
---------


To compile the project, simply navigate to the root of the project and enter the following command:

```
gcc -Wall -Werror -Wextra -pedantic ./src/*.c -lm -o raycaster `sdl2-config --cflags` `sdl2-config --libs`

```


Running
-------

Enter `./raycaster` into your shell.

#### Bibiography
-(https://www.parallelrealities.co.uk/tutorials/#isometric)

-[DrDanick](https://github.com/drdanick)

