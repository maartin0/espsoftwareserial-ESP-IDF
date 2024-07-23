cmake_minimum_required(VERSION 3.5)

idf_component_register(SRCS "src/SoftwareSerial.cpp" "src/SoftwareSerial.h"
                       INCLUDE_DIRS "src"
                       REQUIRES arduino ghostl)

project(espsoftwareserial)
