cmake_minimum_required(VERSION 3.8)
project(dnspod_sr_master)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES
        next/storage.c
        next/storage.h
        src/author.c
        src/author.h
        src/config.h
        src/control.c
        src/control.h
        src/datas.c
        src/datas.h
        src/dns.c
        src/dns.h
        src/event.c
        src/event.h
        src/init.c
        src/io.c
        src/io.h
        src/memory.c
        src/memory.h
        src/net.c
        src/net.h
        src/storage.c
        src/storage.h
        src/update.c
        src/update.h
        src/utils.c
        src/utils.h
        tool/client.c)

add_executable(dnspod_sr_master ${SOURCE_FILES})