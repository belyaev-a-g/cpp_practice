cmake_minimum_required(VERSION 3.22)
project(atomic_flag)

set(CMAKE_CXX_STANDARD 20)

add_executable(atomic_flag main.cpp)

target_link_libraries(atomic_flag pthread)