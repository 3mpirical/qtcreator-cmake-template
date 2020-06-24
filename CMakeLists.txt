cmake_minimum_required(VERSION 3.5)

project(mvc LANGUAGES CXX)

include_directories("${CMAKE_SOURCE_DIR}/include")

set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(mvc
    # Main
    src/main.cpp

    # Headers

    # Implementations
)
