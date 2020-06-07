CMAKE_MINIMUM_REQUIRED(VERSION 2.8)
project(io)

SET(SRC readn.c writen.c readline.c socket_util.c)

ADD_LIBRARY(${PROJECT_NAME} ${SRC})
