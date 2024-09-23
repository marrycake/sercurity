project(first) 

file(GLOB FIRST_HEADER "${CMAKE_CURRENT_SOURCE_DIR}/header/*.h")
file(GLOB FIRST_SOURCE "${CMAKE_CURRENT_SOURCE_DIR}/src/*.cpp")

add_executable(uBlock_Windows_128_128 "${CMAKE_CURRENT_SOURCE_DIR}/src/uBlock_Windows_128_128.cpp") 
add_executable(uBlock_Windows_128_256 "${CMAKE_CURRENT_SOURCE_DIR}/src/uBlock_Windows_128_256.cpp") 
add_executable(uBlock_Windows_256_256 "${CMAKE_CURRENT_SOURCE_DIR}/src/uBlock_Windows_256_256.cpp") 