add_executable(boundary_air_test boundary_air_test.cc)
target_link_libraries(boundary_air_test starkware_gtest algebra air_test_utils periodic_column neighbors)
add_test(boundary_air_test boundary_air_test)
