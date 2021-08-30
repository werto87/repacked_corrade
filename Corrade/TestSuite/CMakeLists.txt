target_sources(${TARGET_NAME} PRIVATE
TestSuite.h
visibility.h
Tester.cpp
Tester.h
Comparator.h
Comparator.cpp
)
add_subdirectory(Implementation)
add_subdirectory(Compare)
