add_library(utils utils.cpp utils.hpp)

add_executable(main main.cpp)

target_link_libraries(main utils)