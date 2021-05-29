cmake_minimum_required(VERSION 3.0)

set(CMAKE_C_STANDARD 99)

SET(CMAKE_BUILD_TYPE Debug)

project(Lab2_demo)

add_subdirectory(cURL)

add_subdirectory(fn_ptr)
add_subdirectory(getopt)
add_subdirectory(pthreads)
add_subdirectory(times)