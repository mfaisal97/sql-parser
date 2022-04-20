cmake_minimum_required(VERSION 3.15)

project(sql-parser)

set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED True)
set(CMAKE_CXX_FLAGS "-O3")


add_subdirectory(src)

add_executable(example "example/example.cpp")
target_link_libraries(example PUBLIC src)
#target_include_directories(planner PRIVATE .)
