cmake_minimum_required(VERSION 3.21)
project(LAB3 C)

set(CMAKE_C_STANDARD 11)
set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${CMAKE_CURRENT_SOURCE_DIR})
add_executable(mergeSort t0/Task_0a/lab3_mergesort.c)
add_executable(PrintHex t0/Task_0b/printHex.c)
add_executable(T1a t1a/main.c)
add_executable(T1c t1c/task1c.c)
add_executable(T2 t2/task2b.c)
