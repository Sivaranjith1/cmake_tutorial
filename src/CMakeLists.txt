file(GLOB SOURCES_H "*.h")
file(GLOB SOURCES_C "*.cpp")
add_library(hello ${SOURCES_C} ${SOURCES_H})

target_include_directories(hello PUBLIC "${CMAKE_CURRENT_SOURCE_DIR}/")