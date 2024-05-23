cmake_minimum_required(VERSION 3.28)
project(dynamicAllocation)

set(CMAKE_CXX_STANDARD 17)

add_executable(dynamicAllocation main.cpp
        allocation.cpp
        Allocation.h)
