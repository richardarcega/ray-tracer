cmake_minimum_required(VERSION 3.25)
project(ray_tracing)

set(CMAKE_CXX_STANDARD 17)

add_executable(ray_tracing main.cc vec3.h ray.h color.h hittable.h sphere.h hittable_list.h rtweekend.h camera.h)
