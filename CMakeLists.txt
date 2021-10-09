project (labsp)

include_directories(src)

set(SOURCES src/main.cpp)

file(GLOB SOURCES "src/*.cpp")

add_executable(book ${SOURCES})
