cmake_minimum_required(VERSION 3.28)
project(p0)

set(CMAKE_CXX_STANDARD 17)
include_directories(${PROJECT_SOURCE_DIR}/include)
add_executable(p0 main.cpp
        include/State.h
        source/State.cpp)
