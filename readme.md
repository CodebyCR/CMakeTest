<H1> A simple modern CMake project.</H1>

*I write this project, because I was struggle to include only Header directories.
<br>I hope this helps other people to work with CMake.*

- this project contains a subdirectory with two header files

<H3>The directory tree is:</H3>

``` 
CMakeTest
    |
    |  - main.cpp
    |  - CMakeLists.txt
    |  - README.md
    |
    |  - Container
    |     | - ContainerOne.hpp
    |     | - ContainerTwo.hpp
    |     | - CMakeLists.txt
    |
    |  - tests
    |     | - test.cpp
    |
    |  - cmake-build-debug
    |     | - some files that cmake creates..
