set(TARGET basic_gemm)

#build test
add_executable(${TARGET} basic_gemm.cpp)
target_link_libraries(${TARGET} GTest::gtest GTest::gtest_main)
