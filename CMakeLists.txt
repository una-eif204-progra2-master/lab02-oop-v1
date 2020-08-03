cmake_minimum_required(VERSION 3.14)
project(lab02-oop)

set(CMAKE_CXX_STANDARD 17)

set(SOURCE_FILES Main.cpp Person.cpp Person.h Professor.cpp Professor.h
        Administrative.cpp Administrative.h University.cpp University.h)

add_executable(lab02-oop ${SOURCE_FILES})