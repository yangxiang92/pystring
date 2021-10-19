cmake_minimum_required(VERSION 3.10)

project(pystring)

add_library(pystring STATIC pystring.cpp)
target_include_directories(pystring PUBLIC ${CMAKE_CURRENT_LIST_DIR})