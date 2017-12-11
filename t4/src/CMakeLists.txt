
include_directories("../include")
LINK_DIRECTORIES(${CMAKE_CURRENT_SOURCE_DIR}/../lib)

ADD_EXECUTABLE(main main.c)
link_libraries(hello.lib)
TARGET_LINK_LIBRARIES(main hello.lib)

