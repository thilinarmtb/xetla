set(TARGET sdp)

#build test
add_executable(${TARGET} scaled_dot_product_attention.cpp)
target_link_libraries(${TARGET} GTest::gtest GTest::gtest_main)
