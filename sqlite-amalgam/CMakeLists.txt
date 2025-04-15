cmake_minimum_required(VERSION 3.30 FATAL_ERROR)

add_library(sqlite STATIC
    sqlite3.c
    shell.c
)

target_include_directories(sqlite PUBLIC $<BUILD_INTERFACE:${CMAKE_CURRENT_LIST_DIR}>)
