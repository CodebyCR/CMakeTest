#Simple CMake Project with two header files in a subdirectory.

cmake_minimum_required(VERSION 3.22)
set(PROJECT_NAME "TestProject")
project(${PROJECT_NAME})

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_CXX_EXTENSIONS OFF)


add_subdirectory(Container)
set(CONTAINER_SOURCE_DIR ${CMAKE_CURRENT_SOURCE_DIR}/Container)


add_executable(${PROJECT_NAME}
        main.cpp
        ${CONTAINER_SOURCE_DIR})
