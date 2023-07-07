
find_package(OpenCV REQUIRED)
add_executable(besier main.cpp)

target_link_libraries(main  ${OpenCV_LIBS})

