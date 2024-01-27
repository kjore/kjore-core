cmake_minimum_required(VERSION 3.24)
project(kjore_core)

set(CMAKE_CXX_STANDARD 23)

include_directories(include)

add_library(kjore_core STATIC
        src/source.cpp)

add_subdirectory(examples/kjore_app_example EXCLUDE_FROM_ALL)