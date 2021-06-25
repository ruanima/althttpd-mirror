#版本要求
cmake_minimum_required(VERSION 3.0.0)
#项目信息
project(althttpd VERSION 0.1.0)

#include(CTest)
#enable_testing()
#编译执行二进制
add_executable(althttpd althttpd.c)
add_compile_options(-Os -Wall -Wextra)