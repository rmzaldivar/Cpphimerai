# CMakeList.txt : CMake project for Cpphimerai, include source and define
# project specific logic here.
#
cmake_minimum_required (VERSION 3.8)

project ("Cpphimerai")

# Add source to this project's executable.
add_executable (Cpphimerai "src/Cpphimerai.cpp" "include/Cpphimerai.h")

if (CMAKE_VERSION VERSION_GREATER 3.12)
  set_property(TARGET Cpphimerai PROPERTY CXX_STANDARD 20)
endif()

# TODO: Add tests and install targets if needed.
