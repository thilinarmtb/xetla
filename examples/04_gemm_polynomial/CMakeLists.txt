set(TARGET gemm_polynomial)

#build test
add_executable(${TARGET} gemm_polynomial.cpp)
target_link_libraries(${TARGET} GTest::gtest GTest::gtest_main)
