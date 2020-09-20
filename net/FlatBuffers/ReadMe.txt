To build the binaries under Windows, with Visual Studio 2019:

1) Install CMake (best to add it to the Path)
2) Run cmake -G "Visual Studio 16 2019" -A x64 (or -A Win32)
3) Open the generated VS solution and build the BUILD_ALL project.