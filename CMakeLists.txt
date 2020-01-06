cmake_minimum_required(VERSION 3.14)
project(c_datastruct C)

set(CMAKE_C_STANDARD 11)

include_directories(03)

add_executable(c_datastruct
        03/01_List.c
        03/02_LinkList.c
        03/03_StaticLinkList.c
        04/01_Stack.c
        04/02_DoubleStack.c
        04/03_LinkStack.c
        04/04_Fibonacci.c
        04/05_Queue.c
        04/06_LinkQueue.c
        05/01_String.c
        05/02_KMP.c
        06/01_BiTreeArray.c
        06/02_BiTreeLink.c
        06/03_ThreadBinaryTree.c
        07/01_CreateMGraph.c
        07/02_CreateALGraph.c
        07/03DFS_BFS.c
        07/04DFS_BFS.c
        07/05_Prim.c
        07/06_Kruskal.c
        07/07_Dijkstra.c
        07/08_Floyd.c
        07/09_TopologicalSort.c
        07/10_CriticalPath.c
        08/01_Search.c
        08/02_BinarySortTree.c
        08/03_AVLTree.c
        08/04_BTree.c
        08/05_HashTable.c
        09/01_Sort.c)
