cmake_minimum_required(VERSION 3.8)
project(tarea4)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES main.cpp Evaluador.h Evaluador.cpp Mascota.h Mascota.cpp)
add_executable(tarea4 ${SOURCE_FILES})