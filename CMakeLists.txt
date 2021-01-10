cmake_minimum_required(VERSION 3.0)
project(luabridge)

add_library(luabridge INTERFACE)
target_include_directories(luabridge SYSTEM INTERFACE Source)