cmake_minimum_required(VERSION 3.9)

add_executable(list list/tail_list.cpp)

# 添加各个算法测试代码
add_subdirectory(batch_test)
