cmake_minimum_required(VERSION 3.23)
project(ray_tracer)

set(CMAKE_CXX_STANDARD 14)

add_executable(ray_tracer main.cpp vec3.h color.h ray.h)
