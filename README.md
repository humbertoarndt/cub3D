# Cub3D

A project inspired by the game [Wolfenstein 3D](https://en.wikipedia.org/wiki/Wolfenstein_3D). The goal is to use raycasting to implement a dynamic view inside a maze using the [miniLibX](https://github.com/42Paris/minilibx-linux). This is a group project, my partner this time was the great [Gabriel Henaut](https://github.com/GabrielHenaut).

<div align="center">

![Cub3Ds' exibition](https://github.com/humbertoarndt/cub3D/blob/master/img/cub3d.gif)  

</div>

## Introduction

The principle tool to develop this project is the **raycasting**, a technique to create a 3D perspective in a 2D map. The idea behind it is that the player's view location send rays to check the distance until a wall, so the program can calculate it's hight and if a collision happens. [3DSage](https://www.youtube.com/@3DSage) have a really good video about it.

## Usage

Clone the project and move into its directory.

```sh
git clone https://github.com/humbertoarndt/cub3D.git
```

Compile the program using `make`

```sh
make
```

Run the program with the following arguments, the maps can be found at `test` directory.

```sh
./cub3D <path_to_map.cub>
```

If `<path_to_map.cub>` is valid the program will run and the map will be renderized, you can use `WASD` keys to move and `LEFT/RIGHT ARROW` keys to rotate the camera. Press `ESC` or the `X`button to end the program. Else an error message will be displayed. 

## References

[Lode's Computer Graphics Tutorial](https://lodev.org/cgtutor/raycasting.html)  
[Make Your Own Raycaster Part 1](https://www.youtube.com/watch?v=gYRrGTC7GtA)