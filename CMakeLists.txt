cmake_minimum_required(VERSION 3.0)

project(GLAD LANGUAGES C)

add_library(glad include/glad/glad.h include/KHR/khrplathorm.h src/glad.c)
target_include_directories(glad PUBLIC include/)
