cmake_minimum_required(VERSION 3.7)
project(Tarea)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES main.cpp Evaluador.cpp Evaluador.h)
add_executable(Tarea ${SOURCE_FILES})