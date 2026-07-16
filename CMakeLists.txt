cmake_minimum_required(VERSION 3.20)
project(inflation_calculator LANGUAGES CXX)
set(CMAKE_CXX_STANDARD 17)
add_executable(inflation inflation/inflation.cpp)
