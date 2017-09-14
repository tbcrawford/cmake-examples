cmake_minimum_required(VERSION 3.0)

SET(CMAKE_BUILD_TYPE Debug)
SET(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++14")

project(cmake-test)

add_executable(goodbye src/goodbye.cpp)

install(TARGETS goodbye DESTINATION bin)