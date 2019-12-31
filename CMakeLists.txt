cmake_minimum_required(VERSION 3.15)
project(tulipindc)

set(CMAKE_CXX_STANDARD 20)

add_executable(tulipindc main.cpp)

target_link_libraries(tulipindc ${CMAKE_SOURCE_DIR}/libindicators.a)
