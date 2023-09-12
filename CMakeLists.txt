cmake_minimum_required(VERSION 3.5)

project(cmdline VERSION 0.1 LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(test cmdline.h test.cpp)
add_executable(test2 cmdline.h test2.cpp)
