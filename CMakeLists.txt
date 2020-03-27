cmake_minimum_required(VERSION 3.10)

#project(ZenovaGUI)

file(GLOB_RECURSE SOURCE_LIST
    "src/*.h"
    "src/*.cpp"
)

add_executable(ZenovaGUI
    ${SOURCE_LIST}
)

target_link_libraries(ZenovaGUI Common)