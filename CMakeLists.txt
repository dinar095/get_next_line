cmake_minimum_required(VERSION 3.17)
project(desausag C)

set(CMAKE_C_STANDARD 99)
add_definitions(-D BUFFER_SIZE=1)

add_executable(desausag get_next_line.c get_next_line_utils.c get_next_line.h main.c main.c)

