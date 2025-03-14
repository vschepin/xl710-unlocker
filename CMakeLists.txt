cmake_minimum_required(VERSION 3.13)
project(xl710_unlock)

set(SRC
        xl710_unlock.c
        syscalls.h
)

add_executable(xl710_unlock ${SRC})