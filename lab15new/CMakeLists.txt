cmake_minimum_required(VERSION 3.27)
project(lab15new C)

set(CMAKE_C_STANDARD 11)

add_executable(lab15new main.c
        matrix.c
        libs/data_structures/matrix/matrix.h
)

dd_executable(lab15new main.c
        libs/data_structures/matrix/matrix.h)

