cmake_minimum_required (VERSION 2.6)
# project (CPP_UTILS_LIB)

# set(CMAKE_CXX_COMPILER "/usr/lib/colorgcc/bin/g++")
#
# set (CXX_FLAGS "-Wall -Wextra -pedantic -Weffc++ -Wshadow "
#                "-Wpointer-arith -Wcast-qual "
#                "-ggdb -fprofile-arcs -ftest-coverage -std=c++0x")
# add_definitions( ${CXX_FLAGS} )

include_directories (../lib)
# aux_source_directory(../src CPP_UTILS_LIB_SOURCES)

# add_library (CppUtils SHARED ${CPP_UTILS_LIB_SOURCES})
# target_link_libraries(CppUtils pthread rt gcov mysqlclient)

# add_library (CppUtils SHARED ${CPP_UTILS_LIB_SOURCES})


add_executable(project_seed main.cpp)
target_link_libraries(project_seed subsystem_1)