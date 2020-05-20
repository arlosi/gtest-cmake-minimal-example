cmake_minimum_required(VERSION 3.16)
project(GoogleTestExample)

enable_testing()
include(GoogleTest)
set(gtest_force_shared_crt ON CACHE BOOL "" FORCE)

add_subdirectory("${PROJECT_SOURCE_DIR}/extern/googletest" "extern/googletest")
add_subdirectory(tests)

