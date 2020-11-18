cmake_minimum_required(VERSION 3.10)

# set the project name
project(Quack)

# C++ version
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED True)

# flags
#set(CMAKE_CXX_FLAGS "-Wall -Wextra -O2")

# add the executable
add_executable(quack src/main.cpp)

# link libraries
#target_link_libraries(quack sfml-graphics sfml-window sfml-system)
