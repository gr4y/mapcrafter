add_executable(mapcrafter_markers mapcrafter_markers.cpp)
add_executable(nbtdump nbtdump.cpp)
add_executable(testconfig testconfig.cpp)
add_executable(testtextures testtextures.cpp)

target_link_libraries(mapcrafter_markers mapcraftercore)
target_link_libraries(nbtdump mapcraftercore)
target_link_libraries(testconfig mapcraftercore)
target_link_libraries(testtextures mapcraftercore)

install(TARGETS mapcrafter_markers DESTINATION bin)