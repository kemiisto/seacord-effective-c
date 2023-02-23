project(seacord-effective-c)

cmake_minimum_required(VERSION 3.0)

# set(CMAKE_VERBOSE_MAKEFILE ON)

# https://cmake.org/cmake/help/latest/prop_tgt/C_STANDARD.html#prop_tgt:C_STANDARD
set(CMAKE_C_STANDARD 11)

add_compile_options(/W4 /WX)

add_executable(01-hello 01/hello.c)
add_executable(02-swap 02/swap.c 02/swap_test.c)
add_executable(02-static 02/static.c)
