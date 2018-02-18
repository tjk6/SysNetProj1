cmake_minimum_required(VERSION 3.8)
project(project1)

set(CMAKE_C_STANDARD 99)

set(SOURCE_FILES main.c server.c server.h)
add_executable(project1 ${SOURCE_FILES})