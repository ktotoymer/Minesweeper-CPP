cmake_minimum_required(VERSION 3.28)
project(Minesweeper_CPP)

set(CMAKE_CXX_STANDARD 17)

add_executable(Minesweeper_CPP main.cpp
        MineSweeper.cpp
        MineSweeper.h)
