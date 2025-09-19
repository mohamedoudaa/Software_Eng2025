#add the executable test named Test_Hello
add_executable(Test_Hello test-hello.cpp)
target_link_libraries(Test_Hello PUBLIC basic)
add_test( NAME Test_Hello COMMAND Test_Hello)
#add the executable test named Test_Version
add_executable(Test_Version test-version.cpp)
target_link_libraries(Test_Version PUBLIC basic)
add_test( NAME Test_Version COMMAND Test_Version)
