cmake_minimum_required(VERSION 2.8.12)

project(spv-strip-reflect)

add_definitions(-D_CRT_SECURE_NO_WARNINGS)

add_executable(spirv-strip-reflect
    ${CMAKE_CURRENT_SOURCE_DIR}/stripper.cpp
    ${CMAKE_CURRENT_SOURCE_DIR}/main.cpp
)
