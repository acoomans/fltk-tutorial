cmake_minimum_required (VERSION 2.6)

project (Tutorial)
set(Tutorial_VERSION_MAJOR 1)
set(Tutorial_VERSION_MINOR 0)


find_package(FLTK REQUIRED)
find_package(OpenGL REQUIRED)

add_executable(hello hello.cxx)
target_link_libraries(hello fltk fltk_images fltk_gl)