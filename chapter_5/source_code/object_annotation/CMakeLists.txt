cmake_minimum_required(VERSION 2.8)
project( object_annotation )
find_package( OpenCV REQUIRED )
add_executable( object_annotation object_annotation.cpp )
target_link_libraries( object_annotation ${OpenCV_LIBS} )
