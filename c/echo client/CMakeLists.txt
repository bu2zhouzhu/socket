cmake_minimum_required(VERSION 3.9)
project(untitled C)

set(CMAKE_C_STANDARD 99)

add_executable(untitled TCPEchoClient4.c Practical.h DieWithMessage.c)