target_sources(${TARGET_NAME} PRIVATE
Resource.cpp
Sha1.cpp
TweakableParser.cpp
Tweakable.cpp
Resource.h
DebugStl.h
TypeTraits.h
Directory.h
AbstractHash.h
MurmurHash2.h
Directory.cpp
Format.h
Unicode.cpp
rc.cpp
FileWatcher.cpp
Algorithms.cpp
String.h
Utility.h
Memory.h
System.h
Endianness.h
Arguments.cpp
visibility.h
utilities.h
Algorithms.h
String.cpp
Configuration.h
ConfigurationGroup.h
StlForwardArray.h
Debug.h
StlMath.h
Move.h
FormatStl.h
Assert.h
Debug.cpp
StlForwardVector.h
StlForwardString.h
ConfigurationGroup.cpp
Tweakable.h
ConfigurationValue.h
Configuration.cpp
Sha1.h
EndiannessBatch.h
Macros.h
ConfigurationValue.cpp
MurmurHash2.cpp
System.cpp
TweakableParser.h
VisibilityMacros.h
FileWatcher.h
Format.cpp
Arguments.h
StlForwardTuple.h
Unicode.h
)

if(CORRADE_TARGET_ANDROID)
    target_sources(${TARGET_NAME} PRIVATE
    AndroidLogStreamBuffer.cpp
    AndroidLogStreamBuffer.h
    )
    
endif()


add_subdirectory(Implementation)
