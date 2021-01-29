cmake_minimum_required(VERSION 3.10)
project(kolokwium)
include_directories(include)
add_library(lib STATIC ../zad3/src/libtest.cpp)
link_directories(../zad3/include)
add_executable(Student ../zad3/src/Student.cpp)
target_link_libraries(lib liblib.a)

