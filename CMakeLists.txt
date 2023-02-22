project(seacord-effective-c)

cmake_minimum_required(VERSION 3.0)

# set(CMAKE_VERBOSE_MAKEFILE ON)

# https://cmake.org/cmake/help/latest/prop_tgt/C_STANDARD.html#prop_tgt:C_STANDARD
set(CMAKE_C_STANDARD 11)

add_executable(01-hello 01/hello.c)
