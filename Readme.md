
##cub_3d - 42 Project Readme
#cub_3d

#Table of Contents
Introduction
Project Overview
Installation
Usage
Controls
Map Format
Features
Screenshots
Contributing
License
#Introduction
Welcome to cub_3d, a project inspired by the classic Wolfenstein 3D game, developed as part of the curriculum at 42, a coding school. This project aims to create a simple raycasting game engine that renders a 3D-like view of a maze from a given map.

#Project Overview
The cub_3d project challenges you to create a raycasting engine using the C programming language and the MinilibX library. The engine will read a map file provided as an argument, render a 3D-like representation of the maze, and allow the player to navigate through it.

#Installation
To install cub_3d on your system, follow these steps:

Clone the repository to your local machine.
Navigate to the project directory.
Compile the project using the provided Makefile:
go
Copy code
make
The executable cub3D should now be generated in the project folder.
#Usage
To run the cub_3d game, use the following command:

bash
Copy code
./cub3D path/to/map_file.cub
For example:

bash
Copy code
./cub3D maps/maze.cub
#Controls
W or ↑: Move forward
A or ←: Strafe left
S or ↓: Move backward
D or →: Strafe right
ESC: Exit the game
#Map Format
The map is represented in a specific format in a .cub file. The file contains information about the maze layout, textures, and colors. Here is an example of the map file:

bash
Copy code
R 1920 1080
NO ./textures/north_texture.xpm
SO ./textures/south_texture.xpm
WE ./textures/west_texture.xpm
EA ./textures/east_texture.xpm
S ./textures/sprite_texture.xpm
F 192,192,192
C 128,0,0
1111111111111
1000000000001
1022222222201
1020202022201
1020202022201
1022222222201
1000000000001
1111111111111
#Features
Raycasting rendering engine
Textured walls
Sprite rendering
Player movement and controls
Basic collision detection
Configurable settings through map files
Screenshots
Screenshot 1
Screenshot 2

#Contributing
Contributions to cub_3d are welcome. If you find any bugs or want to propose enhancements, please open an issue or submit a pull request on the project repository.

##License
This project is licensed under the MIT License.

Developed with ❤️ by rdoukali at 42_Heilbronn.