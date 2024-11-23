cmake_minimum_required(VERSION 3.10)

# Project name
project(project VERSION 1.0)

# Specify C++ standard
set(CMAKE_CXX_STANDARD 23)
set(CMAKE_CXX_STANDARD_REQUIRED True)

# Add the executable
add_executable(project src/main.cpp)

# Optionally specify include directories (if you have headers in include/)
target_include_directories(project PUBLIC ${PROJECT_SOURCE_DIR}/include)
