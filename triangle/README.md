# STL Viewer with OpenGL and Qt

## Overview
This project is a simple STL file viewer built using OpenGL for rendering and the Qt framework for the user interface. The viewer allows users to load and display STL (Stereolithography) files, which are commonly used for representing 3D surface geometry.

## Features
- Load and display STL files.
- Customize rendering settings such as lighting and material properties.

## Classes Used
The project uses the following classes:

- **Triangle**: Represents a triangle in 3D space.
- **Triangulation**: Represents a collection of triangles forming a 3D surface.
- **Reader**: Responsible for reading STL files and converting them into triangulations.
- **Writer**: Responsible for writing triangulations into STL files.
- **Point3D**: Represents a point in 3D space.

## Requirements
To use this project, you need the following:

- C++ compiler compatible with C++11 or later.
- OpenGL development libraries.
- Qt framework (version 5 or later).

## Getting Started
Follow these steps to get started with the project:

1. Clone or download this repository to your local machine.
2. Open the project in your preferred IDE or text editor.
3. Make sure you have all the necessary dependencies installed.
4. Build the project using the provided build system (e.g., CMake, qmake).
5. Run the executable to launch the STL viewer application.
6. Use the user interface to open an STL file and view the 3D model.

## Dependencies
This project relies on the following libraries:
- OpenGL: for rendering 3D graphics.
- Qt: for creating the user interface and handling user input.

Ensure that you have the necessary development libraries installed for both OpenGL and Qt.

## License
This project is licensed under the [MIT License](LICENSE).

## Acknowledgments
- The OpenGL and Qt communities for providing excellent documentation and resources.
