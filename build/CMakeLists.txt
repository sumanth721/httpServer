cmake_minimum_required(VERSION 3.22)

project(
    httpServer
    VERSION 1.0
    LANGUAGES C)

add_executable(http ../source/main.c)
