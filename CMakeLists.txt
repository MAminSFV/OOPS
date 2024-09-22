cmake_minimum_required(VERSION 3.10)

project(oopscode C)

set(CMAKE_C_STANDARD 99)
set(CMAKE_C_STANDARD_REQUIRED ON)
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -O2 -Wall -Wextra -Werror")

set(SOURCES oopscode.c)

add_executable(oopscode ${SOURCES})
