cmake_minimum_required(VERSION 3.16 FATAL_ERROR) # Policies <= CMP0097 default to NEW

project(test_template1)

include(cmake_tools/entry/desktop-cpp.cmake)
__install_conan_requirements(MSVC_RUNTIME "dynamic")

# Add your source files and targets here
# Example:
# add_executable(test_template1 main.cpp)
