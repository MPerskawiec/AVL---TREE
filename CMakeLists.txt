cmake_minimum_required(VERSION 3.14)
project(AVL)

set (SRC main.cpp drzewo.cpp przejscia.cpp)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(${PROJECT_NAME} ${SRC})