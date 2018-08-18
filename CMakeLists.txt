cmake_minimum_required(VERSION 3.6)
project(stk)

set(CMAKE_CXX_STANDARD 17)
set(RAW_WAVE_PATH "${CMAKE_CURRENT_LIST_DIR}/rawwaves")

add_subdirectory(src)
add_subdirectory(projects)