# Set the minimum required version of cmake that can be used to compile the project
cmake_minimum_required(VERSION 3.22)

# Set project name and version
# format: project(name VERSION version_number)
project(MyFirstProject 
        VERSION 1.0.0
        LANGUAGES C CXX)

add_executable(Executable main.cpp)
