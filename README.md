# README for 3D Graphics Project

## Overview

This project demonstrates the rendering of various 3D objects, including a cube, a cylinder, and a sphere, using OpenGL, GLFW, GLEW, and SOIL. It also features basic camera movement and object transformations.

## System Requirements

- OpenGL 4.5 or higher
- GLEW
- GLFW3
- SOIL
- GLM (OpenGL Mathematics)
- Assimp (Open Asset Import Library)

## Compilation and Running

### Compilation

To compile the project, use the following command:

g++ -o myProgram main.cpp -lglfw -lGLEW -lGL -lSOIL -lassimp -std=c++11

### Execution

Run the program using:

./myProgram

## Project Structure

- main.cpp: The main program file containing the rendering loop and initialization logic.
- Camera.h: Camera class header for handling view transformations.
- Mesh.h: Mesh class header for managing object meshes.
- Model.h: Model class header for loading and rendering 3D models.
- shader.h: Shader class header for compiling and linking GLSL shaders.
- Shader files (*.vs, *.frag): GLSL shader source files for vertex and fragment shaders.
- Model files (*.obj, *.mtl): Object files and material files for 3D models.

## Features

- Rendering 3D objects: Cube, cylinder, and sphere are rendered with basic shaders.
- Camera control: Use keyboard inputs to manipulate the camera position and orientation.
- Lighting: Simple lighting setup to demonstrate the effect of light on objects.
- Texture Mapping: Demonstrates how to apply textures to 3D objects (to be implemented in Project 10).

## Controls

- Camera Movement: Use the arrow keys to move the camera.
- Shift keys: Hold to accelerate camera movement.
- Control keys: Hold to adjust camera pitch and yaw.
- R key: Reset camera to the initial position.

## Note

Ensure all the dependent libraries (GLFW, GLEW, SOIL, GLM, and Assimp) are installed and properly configured in your development environment. For detailed setup instructions, refer to the documentation of each library.

made by Daniel Saravia and Keelia Mattison