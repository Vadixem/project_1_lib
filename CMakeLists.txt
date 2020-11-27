cmake_minimum_required( VERSION 3.0 )

project( project_1_lib )

add_library( project_1_lib SHARED project_1_lib.h project_1_lib.cpp )
target_include_directories( project_1_lib PUBLIC ${CMAKE_CURRENT_SOURCE_DIR} )