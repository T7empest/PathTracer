cmake_minimum_required(VERSION 3.16)
project(PathTracer)

set(CMAKE_CXX_STANDARD 23)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

set(SOURCES
        src/main.cpp
        src/interval.h
        src/camera.h
        src/material.h
)

include_directories(${CMAKE_SOURCE_DIR}/src)

add_executable(PathTracer ${SOURCES})

