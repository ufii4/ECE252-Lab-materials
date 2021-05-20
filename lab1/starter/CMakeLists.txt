cmake_minimum_required(VERSION 3.0)

set(CMAKE_C_STANDARD 99)

SET(CMAKE_BUILD_TYPE Debug)

project(Lab1_demo)

add_subdirectory(cmd_arg)

add_subdirectory(ls)
add_subdirectory(pointer)
add_subdirectory(segfault)
add_subdirectory(png_util)