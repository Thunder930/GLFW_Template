This is a VERY minimialist setup using [GLEW](https://glew.sourceforge.net/)/[GLFW](https://www.glfw.org/) setup, since linking libraries and projects can be cumbersome for a beginner.
The full source code for both GLEW and GLFW is provided in the external/ folder, which allows for easier debuging and modification of the libaries as needed.
This project is intended to be setup using [CMake](https://cmake.org/). CMake should generate a Visual Studio solution with the template as the default project and GLEW/GLFW properly linked.
This templete uses GLEW 2.2.0 and GLFW 3.4, although the versions can be changed by simply replacing the appropriate files. The structure of the external/ folder, however, should NOT be modified as the CMakeLists is depentented on the current structre.
