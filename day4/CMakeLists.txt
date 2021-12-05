cmake_minimum_required(VERSION 3.16.0)
add_compile_options(-Wall -Wextra -Wpedantic -Werror)

set(CMAKE_CXX_STANDARD 14)

set(CMAKE_EXPORT_COMPILE_COMMANDS "on")

project(advent-of-code)

add_subdirectory(src)

