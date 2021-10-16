cmake_minimum_required( VERSION 3.1 )

if(${CMAKE_VERSION} VERSION_LESS 3.12)
    cmake_policy(VERSION ${CMAKE_MAJOR_VERSION}.${CMAKE_MINOR_VERSION})
endif()

project( project VERSION 0.1 DESCRIPTION "Change me!" )


include_directories(include )
add_executable( ${PROJECT_NAME} src/test.c src/main.c )
