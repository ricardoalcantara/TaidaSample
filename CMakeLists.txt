cmake_minimum_required(VERSION 3.10)

project(taida_sample VERSION 0.0.1 LANGUAGES C)

add_subdirectory("ext/Taida")

add_executable(${PROJECT_NAME} src/main.c)

target_link_libraries(${PROJECT_NAME} taida)

