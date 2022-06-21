cmake_minimum_required(VERSION 3.15)
project(dummy)

add_executable(dummyproj src/main.cpp)
target_include_directories(dummyproj PUBLIC include)