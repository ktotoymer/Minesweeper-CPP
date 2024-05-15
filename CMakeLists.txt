cmake_minimum_required(VERSION 3.28)
project(Minesweeper_CPP_GUI)

set(CMAKE_CXX_STANDARD 17)

find_package(wxWidgets COMPONENTS core base REQUIRED)

include(${wxWidgets_USE_FILE})

add_executable(Minesweeper_CPP_GUI main.cpp)

target_link_libraries(Minesweeper_CPP_GUI ${wxWidgets_LIBRARIES})