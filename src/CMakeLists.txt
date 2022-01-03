include_directories(${PROJECT_SOURCE_DIR}/lib)
add_executable(cmake_fk1 main.cpp)
set_target_properties(cmake_fk1 PROPERTIES
        RUNTIME_OUTPUT_DIRECTORY_DEBUG "${PROJECT_BINARY_DIR}")