cmake_minimum_required(VERSION 3.9)
project(linenoise C)

add_library(linenoise linenoise.c linenoise.h utf8.c utf8.h)

set(LINENOISE_LIB $<TARGET_FILE:linenoise>)
