target_sources(${TARGET_NAME} PRIVATE 
tweakable.h
Resource.h
)

if(CORRADE_TARGET_WINDOWS)
    target_sources(${TARGET_NAME} PRIVATE
    WindowsError.cpp
    WindowsWeakSymbol.cpp
    WindowsError.h
    WindowsWeakSymbol.h
    )
endif()