cmake_minimum_required(VERSION 3.27)
project(learning)

set(CMAKE_CXX_STANDARD 14)

include_directories(src)

add_executable(learning
        src/main.cpp
        src/test_1.cpp
        src/test_1.h)
