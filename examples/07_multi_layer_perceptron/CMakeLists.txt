set(TARGET multi_layer_perceptron)

#build test
add_executable(${TARGET} multi_layer_perceptron.cpp)
target_link_libraries(${TARGET} GTest::gtest GTest::gtest_main)
