cmake_minimum_required(VERSION 3.2)

project(main)

set (SOURCE_EXE main.c)

add_executable(main ${SOURCE_EXE})

target_include_directories(main PRIVATE ${CMAKE_SOURCE_DIR}/libs)

target_link_libraries(main mongoose)