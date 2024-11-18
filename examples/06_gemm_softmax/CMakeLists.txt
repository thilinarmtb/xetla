set(TARGET gemm_softmax)

#build test
add_executable(${TARGET} gemm_softmax.cpp)
target_link_libraries(${TARGET} GTest::gtest GTest::gtest_main)
