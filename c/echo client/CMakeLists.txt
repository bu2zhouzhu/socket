cmake_minimum_required(VERSION 3.9)
project(TCPEchoClient4 C)

set(CMAKE_C_STANDARD 99)

add_executable(TCPEchoClient4 TCPEchoClient4.c Practical.h DieWithMessage.c)