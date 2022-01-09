cmake_minimum_required(VERSION 3.21)
project(learningcpp)

set(CMAKE_CXX_STANDARD 20)

include_directories(.)
include_directories(ch1)

add_executable(learningcpp
        ch1/ex1.cpp)
