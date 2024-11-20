add_executable(test
    std_stu_test.cpp
)

include_directories(${CMAKE_SOURCE_DIR}/std_stu)

target_link_libraries(test PUBLIC
    std_stu
)