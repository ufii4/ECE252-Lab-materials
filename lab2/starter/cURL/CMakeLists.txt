project(cURL)

set(CMAKE_C_STANDARD 99)

add_executable(cURL_simple main_simple.c)
add_executable(cURL_write_header_cb main_write_header_cb.c)
add_executable(cURL_write_callback main_write_callback.c)

find_package(CURL REQUIRED)

target_link_libraries(cURL_simple ${CURL_LIBRARIES})
target_link_libraries(cURL_write_header_cb ${CURL_LIBRARIES})
target_link_libraries(cURL_write_callback ${CURL_LIBRARIES})