cmake_minimum_required(VERSION 3.22)

# Set project name and version, and the languages used
# Note: C++ is referred to as CXX within cmakelists. This project supports both C and C++ source files
# format: project(name
#                 VERSION version_number
#                 LANGUAGES languages)
                   
                   
project(IntermediateStructure 
        VERSION 1.0.0
        LANGUAGES C CXX)

add_subdirectory(src)
add_subdirectory(MyClass)