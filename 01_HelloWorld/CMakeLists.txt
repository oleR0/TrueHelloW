project(hello)
cmake_minimum_required(VERSION 2.6)
message("Start building...")
set(CMAKE_INSTALL_PREFIX ${CMAKE_CURRENT_SOURCE_DIR}/build)
file(GLOB CPPS "src/*.cpp")
add_executable(${PROJECT_NAME} ${CPPS})