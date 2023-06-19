# Steps for Cmake:
# 1) Write source files and CmakeLists.txt
# 2) mkdir build
# 3) cd build
# 4) cmake .. -> this command converts cmakelists into make file
# 5) make

# Set the minimum required version of cmake that can be used to compile the project
cmake_minimum_required(VERSION 3.22)

# Set project name and version, and the languages used
# Note: C++ is referred to as CXX within cmakelists. This project supports both C and C++ source files
# format: project(name
#                 VERSION version_number
#                 LANGUAGES languages)
                   
                   
project(MyFirstProject 
        VERSION 1.0.0
        LANGUAGES C CXX)

add_executable(HelloWorld main.cpp)
