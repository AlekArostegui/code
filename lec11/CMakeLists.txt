cmake_minimum_required(VERSION 3.3)
project(lec11 CXX)
include(.eecs230/CMakeLists.txt)

add_test_program(Cons_list_tests
        test/linked_list_tests.cpp
        src/linked_list.cpp src/linked_list.h)

add_test_program(increment_example
        src/increment_example.cpp)