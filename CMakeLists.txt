cmake_minimum_required(VERSION 3.5)
project(Bkina)

set(CMAKE_CXX_STANDARD 14)
set(CMAKE_EXE_LINKER_FLAGS -static)
add_executable(Bkina main.cpp BasicStruct.hpp Command.hpp UserMananger.hpp FileManager.hpp TrainManager.hpp BPlusTree.hpp
        BasicString.hpp BasicStruct.hpp vector.hpp
        bptree.hpp alloc.cpp alloc.h pair.hpp exceptions.h)
