cmake_minimum_required(VERSION 3.14)
project(cllm C)

set(CMAKE_C_STANDARD 23)
set(CMAKE_EXPORT_COMPILE_COMMANDS ON)

add_executable(cllm include/ggml.h src/main.c src/main.h src/ggml.c)
