# engine
Start of 3D geometry engine for simulations.

This branch will be for linux development

Requires GLAD with OpenGL 3.3 or higher
         GLFW
         GLM

Include libraries in /lib and while in /build use command: cmake ..
to build project and use the Makefile generated

or make sure all libraries are installed along with glad being placed somewhere g++ will look for included libraries and use the command:
g++ -o Engine main.cpp glad.c -lglfw -ldl