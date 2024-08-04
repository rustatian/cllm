cmake_minimum_required(VERSION 3.14)
project(zllm C)
set(CMAKE_C_STANDARD 23)

add_executable(zllm include/ggml.h src/main.c src/main.h src/ggml.c)
