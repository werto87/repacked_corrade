target_sources(${TARGET_NAME} PRIVATE
Resource.h
tweakable.h
)

if(CORRADE_TARGET_WINDOWS)
target_sources(${TARGET_NAME} PRIVATE
WindowsError.h
WindowsError.cpp
WindowsWeakSymbol.cpp
WindowsWeakSymbol.h
)   
endif()
