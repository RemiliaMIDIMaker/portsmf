cmake_minimum_required(VERSION 3.0)
project(portsmf)

include_directories(include)
aux_source_directory(source SOURCE_FILES)

add_library(portsmf STATIC ${SOURCE_FILES})
