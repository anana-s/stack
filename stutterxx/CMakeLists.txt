

add_library(stutterxx INTERFACE)
target_include_directories(stutterxx INTERFACE .)

add_executable(stutter stutter.cxx)
target_link_libraries(stutter PUBLIC stutterxx)
