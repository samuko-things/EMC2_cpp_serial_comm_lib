cmake_minimum_required(VERSION 3.16)
project(EMC2_libserial_client_api_cpp LANGUAGES CXX)



include_directories(include)
add_executable( example_control_code examples/example_control_code.cpp )
target_link_libraries( example_control_code serial )

