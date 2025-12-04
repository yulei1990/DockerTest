cmake_minimum_required(VERSION 3.11)

set(VCPKG_ROOT ${CMAKE_CURRENT_SOURCE_DIR}/share/vcpkg/vcpkg_master)
set(CMAKE_TOOLCHAIN_FILE ${VCPKG_ROOT}/scripts/buildsystems/vcpkg.cmake)

message(STATUS "server project CMAKE_TOOLCHAIN_FILE = ${CMAKE_TOOLCHAIN_FILE}")
message(STATUS "server project compiler = ${CMAKE_CXX_COMPILER}")


