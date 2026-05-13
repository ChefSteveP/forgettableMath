cmake_minimum_required(VERSION 3.23)

project(FM)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(hello)
target_sources(hello
	PRIVATE
	src/main.cpp
)

target_include_directories (hello
	PRIVATE
	include/
)
