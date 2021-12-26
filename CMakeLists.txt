cmake_minimum_required(VERSION 3.10)

project(intro-fluid-sim)
include(CTest)

set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED True)

add_subdirectory(include)
add_subdirectory(src)

add_executable(intro-fluid-sim src/main.cpp)
