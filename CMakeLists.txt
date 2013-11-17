cmake_minimum_required(VERSION 2.6)
project(BLAM)

include_directories(include)

add_executable(BLAM
	src/common.c
	src/macro.c
	src/main.c
	src/parse.c
	src/script.c
)

