set(TARGET gemm_large_n)

# build test
add_executable(${TARGET} gemm_large_n.cpp)
target_link_libraries(${TARGET} GTest::gtest GTest::gtest_main)
