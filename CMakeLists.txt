cmake_minimum_required(VERSION 3.14)
project(radix_2_fft C)

set(CMAKE_C_STANDARD 11)

include_directories(.)

add_executable(radix_2_fft_test
        fft_c.c
        fft_c.h
        main.c)
