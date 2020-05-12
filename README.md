# OpenGL2DTexture

OpenGL2DTexture utilizes vertex and fragment shaders to render a 2d texture generated from a .png file to the screen.

OpenGL2DTexture was programmed using C++ and OpenGL and utilizes GL/GLEW for OS compatibility. 

By default, OpenGL2DTexture renders the bears.png image located in the res/textures folder, by using 2 triangles generated using vertex and index buffers that can be modified through geometric transformations using glm and ImGui. 

## Dependencies: 
This C++ & OpenGL project uses the following free libraries:
- stb: https://github.com/nothings/stb
- ImGui: https://github.com/ocornut/imgui
- OpenGL Mathematics (GLM): https://github.com/g-truc/glm
