add_executable(test1 test1.cpp)
target_link_libraries(test1 gtest gtest_main)
gtest_discover_tests(test1)
