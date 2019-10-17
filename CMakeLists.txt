cmake_minimum_required(VERSION 3.10)
project(1stC C)

set(CMAKE_C_STANDARD 11)

add_executable(1stC main.c notmain.c)
target_link_libraries(1stC m)