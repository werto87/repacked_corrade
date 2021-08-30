configure_file(${CMAKE_CURRENT_SOURCE_DIR}/configure.h.cmake
               ${CMAKE_CURRENT_BINARY_DIR}/configure.h)

target_sources(${TARGET_NAME} PRIVATE 
Corrade.h
Tags.h
 )

add_subdirectory(Containers)
add_subdirectory(Interconnect)
add_subdirectory(PluginManager)
add_subdirectory(Utility)





