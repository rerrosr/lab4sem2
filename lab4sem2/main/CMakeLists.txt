cmake_minimum_required(VERSION 3.25)
project(lab4sem2 C)

set(CMAKE_C_STANDARD 99)
add_executable(lab4sem2 main.c)

target_link_libraries(lab4sem2 lib)