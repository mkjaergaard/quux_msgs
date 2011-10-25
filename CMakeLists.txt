cmake_minimum_required(VERSION 2.8)

set(CMAKE_FIND_ROOT_PATH /tmp/sandbox)

find_package(ros_cmake)
#find_package(genmsg)
find_package(gencpp)

add_subdirectory(msg)