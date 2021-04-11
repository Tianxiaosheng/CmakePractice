SET(SRC_DIR main.c)
INCLUDE_DIRECTORIES(/tmp/demo_3/include/hello)
ADD_EXECUTABLE(demo4 ${SRC_DIR})

TARGET_LINK_LIBRARIES(demo4 /tmp/demo_3/lib/libhello.a)
