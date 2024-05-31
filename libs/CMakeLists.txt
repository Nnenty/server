cmake_minimum_required(VERSION 3.2)

project(mongoose)

set(SOURCE_LIB mongoose.c)

add_library(mongoose STATIC ${SOURCE_LIB})