cmake_minimum_required (VERSION 3.1)
project (Raytracer)
file(GLOB SOURCES
    *.h
    *.cpp)

set(CXX_STANDARD_REQUIRED 11)

add_executable(Raytracer ${SOURCES})