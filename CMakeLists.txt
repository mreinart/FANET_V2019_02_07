cmake_minimum_required(VERSION 3.7)
project(FANET_Station)

set(CMAKE_C_STANDARD 11)

include_directories(. /usr/local/include /usr/include)

add_executable(FANET_Station main.c)

target_link_libraries(FANET_Station m mariadb wiringPi)
