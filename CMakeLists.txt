cmake_minimum_required(VERSION 4.2)
project(cplusplus_study)

set(CMAKE_CXX_STANDARD 20)

add_executable(cplusplus_study main.cpp)

add_executable(input_output ch02/input_output/input_output.cpp)
add_executable(input_output2 ch02/input_output/input_output2.cpp)
add_executable(print_ASCII ch02/print_ASCII/print_ASCII.cpp)
add_executable(UNICODE ch02/UNICODE/UNICODE.cpp)
add_executable(sizeof_data_types ch02/sizeof_data_types/sizeof_data_types.cpp)
add_executable(floating_point ch02/floating_point/floating_point.cpp)
add_executable(precision_floating_point ch02/precision_floating_point/precision_floating_point.cpp)