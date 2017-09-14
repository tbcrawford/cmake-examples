cmake_minimum_required(VERSION 3.0)

set(CMAKE_BUILD_TYPE DEBUG)
set(CMAKE_CXX_FLAGS "-std=c++14")

project(cmake-test)

add_executable(opengl src/opengl-test.cpp)

install(TARGETS opengl DESTINATION bin)