cmake_minimum_required(VERSION 3.0)

project(distributedcaching)

add_executable(distributedcaching main.cpp)
add_executable(ApplicationCaching application_caching/application_caching.cpp)

install(TARGETS distributedcaching   DESTINATION bin)
