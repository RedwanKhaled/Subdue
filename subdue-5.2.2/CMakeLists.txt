cmake_minimum_required(VERSION 3.3)
project(subdue_5_2_2)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES
    src/avl.c
    src/avl.h
    src/compress.c
    src/cvtest_main.c
    src/discover.c
    src/dot.c
    src/evaluate.c
    src/extend.c
    src/gendata.c
    src/gm_main.c
    src/gprune_main.c
    src/graph2dot_main.c
    src/graphmatch.c
    src/graphops.c
    src/incboundary.c
    src/inccomp.c
    src/incextend.c
    src/incgraphops.c
    src/incutil.c
    src/labels.c
    src/main.c
    src/mdl_main.c
    src/mpi.c
    src/mpi_main.c
    src/sgiso.c
    src/sgiso2_main.c
    src/sgiso_main.c
    src/subdue.h
    src/subops.c
    src/subs2dot_main.c
    src/test.c
    src/test_main.c
    src/utility.c)

add_executable(subdue_5_2_2 ${SOURCE_FILES})