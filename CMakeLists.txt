cmake_minimum_required(VERSION 3.16)

project(basic)

# we want to use the newest and boldest c++ standard
set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED)

set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${PROJECT_SOURCE_DIR}/bin)

add_executable(basic main.cpp)
