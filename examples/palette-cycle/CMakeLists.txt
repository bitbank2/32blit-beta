cmake_minimum_required(VERSION 3.8)
project (palette-cycle)
include (../../32blit.cmake)
blit_executable (palette-cycle palette-cycle.cpp)
blit_assets_yaml (palette-cycle assets.yml)
