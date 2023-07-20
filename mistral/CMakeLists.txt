add_executable(${PROJECT_NAME} src/main.cpp )
#include_directories(${CMAKE_SOURCE_DIR}/projectB) # include files from ProjectB
#target_link_libraries(projectA projectB)

install(TARGETS ${PROJECT_NAME} RUNTIME DESTINATION bin)