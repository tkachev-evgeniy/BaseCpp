cmake_minimum_required(VERSION 3.5)

project(HW3)
add_executable(HW3 
src/program.cpp)

target_include_directories(HW3 PRIVATE 
${CMAKE_CURRENT_SOURCE_DIR}/include)


#set_target_properties(
#    HW3.exe PROPERTIES
#    CXX_STANDARD 14
#    CXX_STANDARD_REQUIRED ON
#    )
