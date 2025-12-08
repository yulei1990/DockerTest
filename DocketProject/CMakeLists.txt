# 设置 vcpkg 工具链路径，指向子模块内的 vcpkg
set(CMAKE_TOOLCHAIN_FILE ${CMAKE_CURRENT_SOURCE_DIR}/../share/vcpkg/scripts/buildsystems/vcpkg.cmake CACHE PATH "")

# 如果你的CMake版本 >= 3.15，更推荐使用以下方式
# set(CMAKE_TOOLCHAIN_FILE ${CMAKE_CURRENT_SOURCE_DIR}/../share/vcpkg/scripts/buildsystems/vcpkg.cmake)

find_package(fmt CONFIG REQUIRED)
find_package(spdlog CONFIG REQUIRED)