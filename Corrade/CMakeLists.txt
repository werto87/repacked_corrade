target_sources(${TARGET_NAME} PRIVATE
Tags.h
Corrade.h
)
add_subdirectory(Containers)
add_subdirectory(Utility)
add_subdirectory(PluginManager)
add_subdirectory(Interconnect)
add_subdirectory(TestSuite)
configure_file(${CMAKE_CURRENT_SOURCE_DIR}/configure.h.cmake
${CMAKE_CURRENT_BINARY_DIR}/configure.h)
