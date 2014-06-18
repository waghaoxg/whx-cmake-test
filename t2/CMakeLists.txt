cmake_minimum_required(VERSION 2.8)
project(Hello2)
add_subdirectory(src)

install(FILES COPYRIGHT README DESTINATION note)
install(PROGRAMS runhello.bat DESTINATION bin)
