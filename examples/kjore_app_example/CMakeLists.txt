cmake_minimum_required(VERSION 3.24)
project(kjore_app_example)

set(CMAKE_CXX_STANDARD 23)



add_executable(kjore_app_example main.cpp)
target_link_libraries(kjore_app_example PRIVATE kjore_core)