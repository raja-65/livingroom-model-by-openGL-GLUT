# livingroom-model-by-openGL-GLUT

# Living Room Model using OpenGL and GLUT

This project demonstrates a simple 3D model of a living room built using OpenGL and GLUT. The model includes basic furniture items such as a sofa, coffee table, lamp, and a painting on the wall.

## Prerequisites

Before running this project, ensure you have the following dependencies installed:
- OpenGL
- GLUT (OpenGL Utility Toolkit)

## Installation and Usage

1. Clone this repository to your local machine.
2. Navigate to the project directory.
3. Compile the source code using a C/C++ compiler that supports OpenGL.
    ```bash
    gcc -o main main.c -lGL -lGLU -lglut
    ```
4. Run the compiled executable.
    ```bash
    ./main
    ```
5. Once the program is running, you should see the living room model displayed in a new window.

## Controls

- use 1, 2 for lights
- Use the arrow keys to navigate around the room.
- Press 'W' to move forward, 'S' to move backward, 'A' to strafe left, and 'D' to strafe right.
- Use the mouse to look around the room.
- Press 'Esc' to exit the program.

## Files Included

- `main.c`: The main source code file containing the OpenGL rendering code.
- `README.md`: This file providing information about the project.

## Screenshots

![Living Room Model](screenshots/living_room_model.png)

## Acknowledgments

This project was created as a learning exercise and is inspired by various OpenGL tutorials and resources available online.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
