## Getting Started
Clone with 
```bash
git clone -- recursive https://github.com/AndrewCoon/Boiler
```

If submodules break, delete the contents of Boiler/Vendor and run:
```bash
git submodule add -b master https://github.com/glfw/glfw.git Boiler/Vendor/glfw
git submodule add -b master https://github.com/g-truc/glm.git Boiler/Vendor/glm
git submodule add -b c https://github.com/Dav1dde/glad.git Boiler/Vendor/glad
git submodule add -b https://github.com/ocornut/imgui.git Boiler/Vendor/imgui
```

To make:
```bash
# Microsoft Windows
cmake -S .. -B .
...
```

If you compile and run, you should now be at the same point as the [Hello Window](http://www.learnopengl.com/#!Getting-started/Hello-Window) or [Context Creation](https://open.gl/context) sections of the tutorials. Open [main.cpp](https://github.com/Polytonic/Glitter/blob/master/Glitter/Sources/main.cpp) on your computer and start writing code!

## Documentation

Functionality           | Library
----------------------- | ------------------------------------------
OpenGL Function Loader  | [glad](https://github.com/Dav1dde/glad)
Windowing and Input     | [glfw](https://github.com/glfw/glfw)
OpenGL Mathematics      | [glm](https://github.com/g-truc/glm)
ImGui                   | [imgui](https://github.com/ocornut/imgui)