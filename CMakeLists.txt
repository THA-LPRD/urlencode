cmake_minimum_required(VERSION 3.12)
project(UrlEncode)

# Add the source files
add_library(UrlEncode STATIC src/UrlEncode.cpp)

# Include the headers directory
target_include_directories(UrlEncode PUBLIC ${CMAKE_CURRENT_SOURCE_DIR}/src)
