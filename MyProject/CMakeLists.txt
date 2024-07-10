cmake_minimum_required(VERSION 3.20.0)
project(MyProject VERSION 0.1)

add_executable("${CMAKE_PROJECT_NAME}" src/main.c)

target_include_directories("${CMAKE_PROJECT_NAME}" PUBLIC "${PROJECT_BINARY_DIR}")
