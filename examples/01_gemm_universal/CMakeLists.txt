set(TARGET gemm_universal)

#build test
add_executable(${TARGET} gemm_universal.cpp)
target_link_libraries(${TARGET} GTest::gtest GTest::gtest_main)
