cmake_minimum_required(VERSION 4.0)
project(Aeternitas)

# =====

add_subdirectory(engine/graphics)

# =====

add_subdirectory(dev-client)

# =====

include(cmake/Dependencies.cmake)