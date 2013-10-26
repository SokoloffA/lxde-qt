project(lxde-qt)
cmake_minimum_required(VERSION 2.6)

set(INTREE_ROOT_DIR "${CMAKE_BINARY_DIR}/intree/")
set(CMAKE_PREFIX_PATH "${INTREE_ROOT_DIR}/cmake/")

add_subdirectory(libqtxdg)
add_subdirectory(liblxqt)

add_subdirectory(lxqt-about)
