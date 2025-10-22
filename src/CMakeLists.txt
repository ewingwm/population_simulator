add_executable(PopulationSimulator main.cpp)
include_directories(${SDL2_INCLUDE_DIRS})
target_link_libraries(PopulationSimulator ${SDL2_LIBRARIES})