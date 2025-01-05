cmake_minimum_required(VERSION 3.27)
project(SortedMultiMap_fr)

set(CMAKE_CXX_STANDARD 17)

add_executable(SortedMultiMap_fr App.cpp
        ExtendedTest.cpp
        ExtendedTest.h
        ShortTest.cpp
        ShortTest.h
        SMMIterator.cpp
        SMMIterator.h
        SortedMultiMap.cpp
        SortedMultiMap.h)
