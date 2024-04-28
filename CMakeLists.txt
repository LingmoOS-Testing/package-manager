cmake_minimum_required(VERSION 3.29)
project(NewPackageManager)

set(CMAKE_CXX_STANDARD 23)

add_subdirectory(Thirdparty/gobject)

add_executable(NewPackageManager main.cpp)
target_link_libraries(NewPackageManager gobject)