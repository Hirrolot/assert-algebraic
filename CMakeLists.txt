cmake_minimum_required(VERSION 3.0.2)
project(assert-algebraic)

add_library(${PROJECT_NAME} INTERFACE)
target_include_directories(${PROJECT_NAME} INTERFACE ${CMAKE_CURRENT_SOURCE_DIR})
