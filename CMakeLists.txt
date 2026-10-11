cmake_minimum_required(VERSION 3.10)

project(date_class)

set(CMAKE_CXX_STANDARD 14)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

# Set compiler flags for better optimization and warnings
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -O2 -Wall -Wextra -Wpedantic")

# Add the executable
add_executable(code date.cpp)