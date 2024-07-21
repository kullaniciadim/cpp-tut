cmake_minimum_required(VERSION 3.21)

project(cppBuild VERSION 1.0)
 
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

set(SOURCES
	source/main.cpp
)

add_executable(output ${SOURCES})
