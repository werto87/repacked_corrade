target_sources(${TARGET_NAME} PRIVATE 
AbstractHash.h              
Debug.cpp          
Move.h              
System.cpp
Algorithms.cpp              
Debug.h            
MurmurHash2.cpp     
System.h
Algorithms.h                
DebugStl.h         
MurmurHash2.h       
Tweakable.cpp
Directory.cpp      
rc.cpp              
Tweakable.h
Directory.h        
Resource.cpp        
TweakableParser.cpp
Arguments.cpp               
EndiannessBatch.h  
Resource.h          
TweakableParser.h
Arguments.h                 
Endianness.h       
Sha1.cpp            
TypeTraits.h
Assert.h                    
FileWatcher.cpp    
Sha1.h              
Unicode.cpp
FileWatcher.h      
StlForwardArray.h   
Unicode.h
Configuration.cpp           
Format.cpp         
StlForwardString.h  
utilities.h
ConfigurationGroup.cpp      
Format.h           
StlForwardTuple.h   
Utility.h
ConfigurationGroup.h        
FormatStl.h        
StlForwardVector.h  
visibility.h
Configuration.h             
StlMath.h           
VisibilityMacros.h
ConfigurationValue.cpp      
Macros.h           
String.cpp
ConfigurationValue.h        
Memory.h           
String.h
)

if(CORRADE_TARGET_ANDROID)
    target_sources(${TARGET_NAME} PRIVATE
        AndroidLogStreamBuffer.h
        AndroidLogStreamBuffer.cpp  
    )
endif()


add_subdirectory(Implementation)






