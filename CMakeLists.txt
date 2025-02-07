cmake_minimum_required(VERSION 3.5)
project(myapp)

add_executable(myapp src/main.c)
target_link_libraries(myapp mylib)

install(TARGETS myapp DESTINATION bin)

