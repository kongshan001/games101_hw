cmake_minimum_required (VERSION 2.8.11)
project (Transformation)

set(EIGNE3_INCLUDE_DIR "D:/learn/eigen-3.4.0")

include_directories(${EIGNE3_INCLUDE_DIR})

add_executable (Transformation main.cpp)
