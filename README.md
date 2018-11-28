# engine
Start of 3D geometry engine for simulations.

This branch will be for linux development

Requires GLAD with OpenGL 3.3 or higher
         GLFW
         GLM

GLFW Can be installed
Must place contents of glad's "/include" in a folder where gcc will look for included directories

Compile with g++ -o run.exe main.cpp glad.c -lglfw -ldl
Autoconf and automake on the way
