project(hesss)
set(CMAKE_CXX_COMPILER "g++")
set (CMAKE_CXX_FLAGS  "-g -fexec-charset=UTF-8")
include_directories(${PROJECT_SOURCE_DIR}/Include)
aux_source_directory(./Src SrcFiles)
set(EXECUTABLE_OUTPUT_PATH  ${PROJECT_SOURCE_DIR}/Bin)
add_executable(b ${SrcFiles})

