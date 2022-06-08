# Adafruit CCS811 Library
# https://github.com/adafruit/Adafruit_CCS811
# MIT License

cmake_minimum_required(VERSION 3.5)

idf_component_register(SRCS "Adafruit_CCS811.cpp" 
                       INCLUDE_DIRS "."
                       REQUIRES arduino adafruit_busio adafruit_sensor)

project(adafruit_ccs811)
