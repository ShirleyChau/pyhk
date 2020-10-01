cmake_minimum_required(VERSION 2.8.12)
project(pyhk)

add_subdirectory(pybind11)
pybind11_add_module(pyhk src/main.cpp)