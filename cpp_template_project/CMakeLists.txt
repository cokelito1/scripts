cmake_minimum_required(VERSION 2.8)

project(_PROJECTNAME_)

include_directories("include")

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_EXPORT_COMPILE_COMMANDS ON)

add_executable(_PROJECTNAME_ src/main.cpp)
