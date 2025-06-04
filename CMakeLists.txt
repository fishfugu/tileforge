cmake_minimum_required(VERSION 3.10)
project(TileForge)

set(CMAKE_CXX_STANDARD 17)

include_directories(src)
add_executable(tileforge src/main.cpp src/board.cpp)
