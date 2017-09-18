cmake_minimum_required(VERSION 3.8)
project(CSimpleTcp)

set(CMAKE_C_STANDARD 99)

set(SOURCE_FILES
        TcpClient.c
        TcpServer.c
        TcpMultServer.c
        )
add_executable(CSimpleTcp ${SOURCE_FILES})