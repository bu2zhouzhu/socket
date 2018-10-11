cmake_minimum_required(VERSION 3.9)
project(TCPEchoServer4 C)

set(CMAKE_C_STANDARD 99)

add_executable(TCPEchoServer4 TCPEchoServer4.c Practical.h DieWithMessage.c TCPServerUtility.c AddressUtility.c)