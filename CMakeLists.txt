cmake_minimum_required(VERSION 3.25)

# set the project name and version
project(RealLogger VERSION 1.0)

# specify the C++ standard
set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED True)

add_library(RealLogger "real_core/Logger.cpp")
target_include_directories(RealLogger PUBLIC ${CMAKE_CURRENT_SOURCE_DIR}/..)