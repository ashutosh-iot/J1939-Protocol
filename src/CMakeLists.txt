file(GLOB_RECURSE SOURCES LIST_DIRECTORIES true *.h *.c)
add_library(${CMAKE_PROJECT_NAME}_core STATIC ${SOURCES})