cmake_minimum_required(VERSION 3.0)

project(GLAD LANGUAGES C)

set(
    HEADERS

    include/glad/glad.h 
    include/KHR/khrplatform.h
)

add_library(glad src/glad.c ${HEADERS})
target_include_directories(glad PUBLIC include/)
