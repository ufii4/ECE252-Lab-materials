project(pthreads)

set(CMAKE_C_STANDARD 99)

add_executable(pthreads main.c)

find_package(Threads REQUIRED)

target_link_libraries(pthreads "${CMAKE_THREAD_LIBS_INIT}")