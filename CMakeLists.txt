cmake_minimum_required(VERSION 3.10)
project(problem_029 C)

set(CMAKE_C_STANDARD 11)
set(CMAKE_C_STANDARD_REQUIRED ON)

add_executable(code src/main.c)

# Keep output in project root
set_target_properties(code PROPERTIES
  RUNTIME_OUTPUT_DIRECTORY "${CMAKE_SOURCE_DIR}"
)

