cmake_minimum_required(VERSION 3.31)
project(cstdlib C)

set(CMAKE_C_STANDARD 11)

add_library(cstdlib STATIC cstdlib.c)
