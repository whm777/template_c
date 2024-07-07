file(GLOB SOURCE_FILES "${CMAKE_CURRENT_SOURCE_DIR}/*.cpp")

add_executable(module1 ${SOURCE_FILES})

target_include_directories(module1 PRIVATE ../../include/module1)
