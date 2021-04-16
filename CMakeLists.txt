cmake_minimum_required(VERSION 3.17)
project(Client)

set(CMAKE_CXX_STANDARD 14)

add_executable(Client client.cpp client_protocol.h tictac.h)