project(cURL)

set(CMAKE_C_STANDARD 99)

add_executable(cURL_simple main_simple.c)
add_executable(cURL_write_header_cb main_write_header_cb.c)
add_executable(cURL_write_callback main_write_callback.c)