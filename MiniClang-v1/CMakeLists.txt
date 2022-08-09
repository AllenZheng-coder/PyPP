# CMakeList.txt: MiniClang-v1 的 CMake 项目，在此处包括源代码并定义
# 项目特定的逻辑。
#
cmake_minimum_required (VERSION 3.8)

project ("MiniClang-v1")

# 将源代码添加到此项目的可执行文件。
add_executable (MiniClang-v1 "MiniClang-v1.cpp" "MiniClang-v1.h")

if (CMAKE_VERSION VERSION_GREATER 3.12)
  set_property(TARGET MiniClang-v1 PROPERTY CXX_STANDARD 20)
endif()

# TODO: 如有需要，请添加测试并安装目标。
