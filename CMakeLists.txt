cmake_minimum_required(VERSION 3.16)
project(C-GiaMichanikous C)

set(CMAKE_C_STANDARD 99)

add_executable(C-GiaMichanikous main.c)

add_subdirectory(libs)
add_subdirectory(src)
add_subdirectory(tests)
add_subdirectory(etc)