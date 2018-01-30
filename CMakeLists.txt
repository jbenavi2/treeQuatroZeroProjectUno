# cmake_minimum_required(VERSION <specify CMake version here>)
project(treeQuatroZeroProjectUno)

set(CMAKE_CXX_STANDARD 11)

add_executable(treeQuatroZeroProjectUno
        README.md parser.h parser.cc lexer.h lexer.cc inputbuf.cc inputbuf.h)
