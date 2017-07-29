# Pong 2D
![pong2d](https://user-images.githubusercontent.com/9254173/28714943-b26dad7a-738d-11e7-8e3e-0b3a27675217.png)

A 2D version of Pong created using OpenGL and SDL written in C++. This was submitted for the Graphics assignment at the University
of Lincoln. Also see the [3D version of Pong](https://github.com/NevilleKing/Pong3D) submitted for another assignment for this module.

## Playing the Game
The easiest way to download the game is via the [releases page](https://github.com/NevilleKing/Pong2D/releases/latest).

If you have visual studio, you can also generate an sln file by using premake from the command line:

    premake5.bat vs2015
    
Controls are:

###### Player 1
`W` - Up

`S` - Down
###### Player 2
`Up Arrow` - Up

`Down Arrow` - Down

## Dependencies
The game uses the following dependencies:
- glew
- premake
- SDL2
- SOIL
