cmake_minimum_required(VERSION 3.6)
project(cppBasics)

set(CMAKE_CXX_STANDARD 14)

set(TARGET_NAME_HELLO hello_world)

add_executable(${TARGET_NAME_HELLO} hello_world.cpp)
