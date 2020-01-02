cmake_minimum_required(VERSION 3.14)
project(PlayWithDataStructureSourceCode C)

set(CMAKE_C_STANDARD 11)

include_directories(03)

add_executable(PlayWithDataStructureSourceCode
        03/01_List.c
        03/02_LinkList.c
        03/03_StaticLinkList.c)
