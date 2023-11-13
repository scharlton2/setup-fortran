cmake_minimum_required(VERSION 3.21)
project(hello LANGUAGES C CXX Fortran)

include(CTest)
enable_testing()

add_executable(hello_c hw.c)
add_test(hello_c hello_c)

add_executable(hello_cpp hw.cpp)
add_test(hello_cpp hello_cpp)

add_executable(hello_f90 hw.f90)
add_test(hello_f90 hello_f90)
