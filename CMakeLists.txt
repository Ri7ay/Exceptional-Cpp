cmake_minimum_required(VERSION 3.8)
project(ExceptCpp)

find_package(Boost)

set(CMAKE_CXX_STANDARD 20)
#set(CMAKE_CXX_FLAGS "-Wall -Werror")

add_executable(ci_string src/ci_string.cpp)
add_executable(fixed_vector src/fixed_vector)

add_executable(monads1 src/monads1.cpp)
add_executable(monads2 src/monads2.cpp)
add_executable(flatmap src/flatmap.cpp)