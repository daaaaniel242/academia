cmake_minimum_required(VERSION 4.1)
project(academia)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(academia
        main.cpp
        main.h)
