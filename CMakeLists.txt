cmake_minimum_required(VERSION 2.6)

project(libfrdma)

include_directories("${PROJECT_SOURCE_DIR}/include")

add_subdirectory(src)
add_subdirectory(benchmarks)
