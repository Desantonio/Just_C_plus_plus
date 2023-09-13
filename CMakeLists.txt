cmake_minimum_required(VERSION 3.0)
project(C++)

# Add Matplotlib++ as a subdirectory
add_subdirectory(matplotplusplus)

# Add your project's source files
add_executable(your_project_source_files hello.cpp)

# Link your project with Matplotlib++
target_link_libraries(your_project_source_files PRIVATE matplotplusplus)
