cmake_minimum_required(VERSION 3.31)
project(PKS1)

set(CMAKE_CXX_STANDARD 14)

include_directories(KR1)

add_executable(PKS1
        KR1/hello.cpp
        KR1/hello.h
        KR1/main.cpp)
