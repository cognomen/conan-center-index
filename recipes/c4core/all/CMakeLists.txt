cmake_minimum_required(VERSION 3.1)
project(cmake_wrapper LANGUAGES CXX)

include(conanbuildinfo.cmake)
conan_basic_setup(KEEP_RPATHS)

add_subdirectory(source_subfolder)
