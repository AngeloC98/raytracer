cmake_minimum_required(VERSION 3.28)

project(RayTracer LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(raytracer
    src/main.cpp
)
