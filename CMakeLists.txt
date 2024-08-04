cmake_minimum_required(VERSION 3.14)
project(zllm C)
set(CMAKE_C_STANDARD 23)

#add_library(zllm
#        include/ggml.h
#        src/main.c
#        src/main.h
#)

add_executable(zllm include/ggml.h src/main.c src/main.h)
