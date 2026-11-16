cmake_minimum_required(VERSION 3.20)
project(learn_CPU VERSION 1.0 LANGUAGES C)
add_compile_options(-Wall -Wextra -std=c17 -pedantic)
add_executable(seq sequential_access.c)