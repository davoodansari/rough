cmake_minimum_required(VERSION 2.8)

project(rough)

include_directories(/home/dansari/hermes/include)
link_directories("/home/dansari/hermes/lib") 
link_libraries(libhermes3d-cplx-debug.so)
add_executable(${PROJECT_NAME} main.cpp)



