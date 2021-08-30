target_sources(${TARGET_NAME} PRIVATE 
Connection.h
Emitter.h 
Interconnect.h 
Receiver.h 
visibility.h
Connection.cpp 
Emitter.cpp 
Receiver.cpp 
StateMachine.h
)

add_subdirectory(Implementation)






