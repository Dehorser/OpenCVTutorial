cmake_minimum_required(VERSION 3.6)
project(OpenCVTutorial)

find_package( OpenCV REQUIRED )

set(CMAKE_CXX_STANDARD 14)

set(SOURCE_FILES main.cpp)
add_executable(OpenCVTutorial ${SOURCE_FILES})