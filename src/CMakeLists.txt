cmake_minimum_required(VERSION 3.30 FATAL_ERROR)

add_executable(sqlite-mgr main.c)

target_link_libraries(sqlite-mgr PUBLIC sqlite)
