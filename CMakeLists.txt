cmake_minimum_required(VERSION 3.27)
project(lab2)

set(CMAKE_CXX_STANDARD 23)

add_executable(lab2 main.cpp
        bikeConfig.cpp
        bikeConfig.h
        client.cpp
        client.h
        employer.cpp
        employer.h
)
