cmake_minimum_required(VERSION 2.8.8)

# Set the project name.
project(circus)

# Add include directory.
include_directories("include")

# Find all files with .c extension.
file(GLOB SRC "src/*.c")

# Generates a library.
add_library("${PROJECT_NAME}" ${SRC})

