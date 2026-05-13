# lab-5
# Author
Sadia Islam
# Description
This program creates an OpenGL window and renders a single animated rectangle. The rectangle continuously changes its color from red to white in a smooth gradient while simultaneously performing scaling and rotation transformations. The animation is fully time-based, meaning all movements and color transitions happen automatically without any user interaction.
# Language & Tools
 - C++
 - OpenGL (GLFW + GLAD)
VS Code
Windows OS
How to Compile and Run
Open the project folder in the terminal or VS Code.
Compile the source file (main.cpp) using your OpenGL build setup (GLFW + GLAD configured).
Run the generated executable file.
An OpenGL window will open and the animation will start automatically.
Key Functionality
Rectangle Animation
The rectangle starts with a pure red color.
It gradually transitions to white using smooth interpolation.
The color change is continuous and time-based.
Movement and Effects
Scaling: The rectangle grows and shrinks smoothly over time.
Rotation: It rotates continuously around both the X-axis and Y-axis.
These combined transformations create a simple 3D-like animated effect.
Window Setup
Window title: Animated Rectangle - OpenGL
Displays a single animated rectangle only
Runs in an infinite loop until manually closed
Proof of Execution
A screenshot showing the OpenGL window along with the VS Code terminal output is attached in the classroom submission.
