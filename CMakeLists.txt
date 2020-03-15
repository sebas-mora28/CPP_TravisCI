cmake_minimum_required(VERSION 3.2)
project(CPP_TravisCI)

set(CMAKE_CXX_STANDARD 14)

add_executable(CPP_TravisCI src/Calculator.cpp src/main.cpp test/calculator.test.cpp )