cmake_minimum_required(VERSION 3.10)

project(helloworld)

add_subdirectory(src)
add_executable(helloworld main.cpp)
target_link_libraries(helloworld PRIVATE hello)