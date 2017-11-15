cmake_minimum_required(VERSION 3.0)

set(CMAKE_CXX_STANDARD 14)

project(extra)

# add_library(extra STATIC ${CMAKE_CURRENT_SOURCE_DIR}/sort_two_containers.cpp)

add_executable(extra ${CMAKE_CURRENT_SOURCE_DIR}/sort_two_containers.cpp)
target_link_libraries(extra)
