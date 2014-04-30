cmake_minimum_required (VERSION 2.6)
project (tcp_server)
include_directories("${PROJECT_BINARY_DIR}")
add_executable(tcp_server tcp_server.cpp)

