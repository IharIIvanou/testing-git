cmake_minimum_required(VERSION 2.6)
project(testing_git)

add_executable(testing_git main.cpp)

install(TARGETS testing_git RUNTIME DESTINATION bin)
