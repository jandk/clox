cmake_minimum_required(VERSION 3.9)
project(clox C)

set(CMAKE_C_STANDARD 99)

include_directories(include)

add_executable(clox clox.c src/chunk.c src/debug.c src/memory.c src/value.c)
