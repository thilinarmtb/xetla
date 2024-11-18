set(TARGET gru_fwd)

# build test
add_executable(${TARGET} gate_recurrent_unit.cpp)
target_link_libraries(${TARGET} GTest::gtest GTest::gtest_main)
