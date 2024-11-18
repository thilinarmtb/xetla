set(TARGET batch_gemm)

#build test
add_executable(${TARGET} batch_gemm.cpp)
target_link_libraries(${TARGET} GTest::gtest GTest::gtest_main)
