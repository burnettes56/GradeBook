cmake_minimum_required(VERSION 3.10)
project(GradeBook)

set(CMAKE_CXX_STANDARD 11)

add_executable(GradeBook main.cpp Student.cc Student.h Course.cc Course.h)