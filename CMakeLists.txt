cmake_minimum_required(VERSION 3.27)
project(CustomPtr)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(CustomPtr
        README.md
        shared_ptr.cpp
        shared_ptr.h)
