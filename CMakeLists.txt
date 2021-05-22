cmake_minimum_required(VERSION 3.1)

project(SFMLTest)

find_package(SFML COMPONENTS graphics window system REQUIRED)
add_executable(SFMLTest main.cpp)
target_link_libraries(SFMLTest sfml-graphics sfml-window sfml-system)