cmake_minimum_required(VERSION 2.8.0)

project(cxx11)

file(GLOB cmake_files ${CMAKE_CURRENT_SOURCE_DIR}/cmake/*.cmake)
install(FILES ${cmake_files} DESTINATION share/cmake)
