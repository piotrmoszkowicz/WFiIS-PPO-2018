cmake_minimum_required(VERSION 3.0.0)
project(asdf VERSION 0.1.0)

add_executable(
  asdf lab12.cpp
  Fraction.h
  Fraction.cpp
  FractionArray.h
  FractionArray.cpp
  Maths.h
  Maths.cpp
)
add_compile_options( -Wall -g)

set(CPACK_PROJECT_NAME ${PROJECT_NAME})
set(CPACK_PROJECT_VERSION ${PROJECT_VERSION})
include(CPack)
