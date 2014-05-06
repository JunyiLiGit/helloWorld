include_directories(${CMAKE_SOURCE_DIR}/include)
add_executable(helloWorld greetings.C)
target_link_libraries(helloWorld helloworld) 
install(TARGETS helloWorld DESTINATION bin)
