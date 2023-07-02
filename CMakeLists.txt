cmake_minimum_required(VERSION 3.0)

project(distributedcaching)

add_executable(distributedcaching main.cpp)

install(TARGETS distributedcaching RUNTIME DESTINATION bin)
