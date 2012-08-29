cmake_minimum_required(VERSION 2.8)
project(cob_extern)

find_package(catkin REQUIRED)

catkin_stack()

add_subdirectory(libntcan)
add_subdirectory(libphidgets)
add_subdirectory(libmesasr)
add_subdirectory(libpcan)

