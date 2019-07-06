# CMake 最低版本号要求
cmake_minimum_required (VERSION 2.8)
# 项目信息
project (Demo1)
# 指定生成目标
add_executable (Demo main.c)

# {

# define TargetOperatingSystem
set (CMAKE_SYSTEM_NAME linux)

# Optional define TargetOS HW or CPU type, like arm x86 etc.
set (CMAKE_SYSTEM_PROCESSOR arm64)

# set c languange compiler path or absorlute path
set (CMAKE_C_COMPILER /usr/bin/aarch64-linux-gnu-gcc)


# set c++ languange compiler path or absorlute path
set (CMAKE_CXX_COMPILER /usr/bin/aarch64-linux-gnu-cpp)


# }
