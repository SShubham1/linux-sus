cmake_minimum_required(VERSION 3.2)
project(linux-2.0)

set(SOURCE_FILES main.c)

add_executable(main ${SOURCE_FILES})
target_link_libraries(main)
install(TARGETS main)
