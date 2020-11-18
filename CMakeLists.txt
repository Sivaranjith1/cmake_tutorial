cmake_minimum_required(VERSION 3.10)

project(helloworld)
file(GLOB helloworld_SRC
    "*.h"
    "*.cpp"
)

add_executable(helloworld ${helloworld_SRC})