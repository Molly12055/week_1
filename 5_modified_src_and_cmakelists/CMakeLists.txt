cmake_minimum_required(VERSION 3.16)

project(modified_src_and_cmakelists
  VERSION 0.0.1
  LANGUAGES CXX
)

set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${CMAKE_BINARY_DIR}/bin)

add_subdirectory(src)
