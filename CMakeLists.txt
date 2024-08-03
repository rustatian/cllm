cmake_minimum_required(VERSION 3.14)
project(zllm C CXX)

#add_library(zllm
#        include/ggml.h
#        src/main.c
#        src/main.h
#)

add_executable(zllm include/ggml.h src/main.c src/main.h)
