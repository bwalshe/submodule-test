cmake_minimum_required(VERSION 3.1)

project(HelloEigen VERSION 1.0
                   DESCRIPTION "Test to see how submodules work."
                   LANGUAGES CXX)


add_executable(hello_eigen main.cpp)
target_include_directories(hello_eigen PUBLIC external/eigen-git-mirror)
