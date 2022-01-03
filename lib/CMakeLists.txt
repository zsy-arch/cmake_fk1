add_library(cmake_fk1_lib SHARED my_math.cpp my_math.h)
set_target_properties(cmake_fk1_lib PROPERTIES
        RUNTIME_OUTPUT_DIRECTORY_DEBUG "${PROJECT_BINARY_DIR}")