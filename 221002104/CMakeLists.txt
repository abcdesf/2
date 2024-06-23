cmake_minimum_required (VERSION 3.12)

set(CMAKE_CXX_STANDARD 11)

project (connect6_c++_cmake)

aux_source_directory(. SRC_LIST)

add_executable(main ${SRC_LIST})
