set(TARGET gemm_relu_bias)

#build test
add_executable(${TARGET} gemm_relu_bias.cpp)
target_link_libraries(${TARGET} GTest::gtest GTest::gtest_main)
