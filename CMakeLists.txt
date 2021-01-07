cmake_minimum_required(VERSION 2.6)
project(hello-world-c)
add_executable(hello-world-c main.c)
install(TARGETS hello-world-c DESTINATION bin)
