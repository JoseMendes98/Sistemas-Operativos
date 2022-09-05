cmake_minimum_required(VERSION 3.22)
project(TP_TOLEIRAO C)

set(CMAKE_C_STANDARD 11)

include_directories(.)
include_directories(TP)

add_executable(TP_TOLEIRAO
        TP/SDStore-transf/bcompress.c
        TP/SDStore-transf/bdecompress.c
        TP/SDStore-transf/decrypt.c
        TP/SDStore-transf/encrypt.c
        TP/SDStore-transf/gcompress.c
        TP/SDStore-transf/gdecompress.c
        TP/SDStore-transf/nop.c
        TP/Cliente.c
        TP/experiment.c
        TP/Servidor.c
        TP/servidor.h
        TP/testeZET.c)
