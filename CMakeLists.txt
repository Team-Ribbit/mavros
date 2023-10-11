cmake_minimum_required(VERSION 2.8.3)
project(mavrosmain)

add_subdirectory(libmavconn)
add_subdirectory(mavros)
add_subdirectory(mavros_extras)
add_subdirectory(mavros_msgs)
add_subdirectory(test_mavros)