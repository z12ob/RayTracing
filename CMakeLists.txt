cmake_minimum_required(VERSION 3.10)
project(RayTracingInOneWeekend)

set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_C_COMPILER "D:/mingw64/bin/gcc.exe")
set(CMAKE_CXX_COMPILER "D:/mingw64/bin/g++.exe")

include_directories(include)
add_executable(inOneWeekend src/main.cc)