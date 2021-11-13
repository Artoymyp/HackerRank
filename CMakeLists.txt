cmake_minimum_required(VERSION 3.10)

# set the project name and version
project(MyHackerRankSubmissions VERSION 1.0)

# specify the C++ standard
set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED True)

file(GLOB SOURCE
    "*.h"
    "*.cpp"
    "*.vs"
    "*.fs"
    "*.gs"
)
add_executable(${PROJECT_NAME} ${SOURCE})