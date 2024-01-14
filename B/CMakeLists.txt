add_library(EXAMPLELIB
    example.cpp
)

target_include_directories(EXAMPLELIB PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})