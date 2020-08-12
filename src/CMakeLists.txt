file(GLOB HDR_FILES
        ${PROJECT_SOURCE_DIR}/include/*.h)

file(GLOB SRC_FILES
        ${PROJECT_SOURCE_DIR}/src/*.cpp)

add_executable(bitboo_preprocessing_exec ${HDR_FILES} ${SRC_FILES})
add_library(bitboo_preprocessing ${HDR_FILES} ${SRC_FILES})