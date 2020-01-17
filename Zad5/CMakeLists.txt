cmake_minimum_required(VERSION 2.8.9)
project(Zad5)

include_directories(include)
file(GLOB SOURCES "src/*.cpp")

add_executable(myProgram ${SOURCES})
