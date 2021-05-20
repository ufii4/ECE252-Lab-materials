project(png_util)

set(CMAKE_C_STANDARD 99)

add_executable(png_util main.c zutil.c crc.c lab_png.h zutil.h crc.h)

find_package(ZLIB)
target_link_libraries(png_util ZLIB::ZLIB)