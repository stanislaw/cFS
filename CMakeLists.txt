cmake_minimum_required(VERSION 3.13)

#set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fsanitize=address")
#set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fsanitize=address")
#set(CMAKE_LINKER_FLAGS "${CMAKE_LINKER_FLAGS} -fsanitize=address -lasan")
#set(CMAKE_CXX_FLAGS_DEBUG "${CMAKE_CXX_FLAGS_DEBUG} -fno-omit-frame-pointer -fsanitize=address")
#set(CMAKE_LINKER_FLAGS_DEBUG "${CMAKE_LINKER_FLAGS_DEBUG} -fno-omit-frame-pointer -fsanitize=address")

add_compile_options(-g)

set(MISSION_SOURCE_DIR ${CMAKE_SOURCE_DIR})
#set(CFS_OUTPUT_PATH ${CMAKE_BINARY_DIR}/output)
#set(CFS_INSTALL_PATH ${CMAKE_BINARY_DIR}/installation)
#set(CMAKE_ARCHIVE_OUTPUT_DIRECTORY ${CFS_OUTPUT_PATH})
#set(CMAKE_LIBRARY_OUTPUT_DIRECTORY ${CFS_OUTPUT_PATH})
#set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${CFS_OUTPUT_PATH})
#
#set(CMAKE_INSTALL_PREFIX ${CFS_INSTALL_PATH})

add_subdirectory(cfe)
