target_sources(${TARGET_NAME} PRIVATE
Emitter.cpp
Emitter.h
Receiver.h
Interconnect.h
StateMachine.h
visibility.h
Receiver.cpp
Connection.h
Connection.cpp
)
add_subdirectory(Implementation)
