cmake_minimum_required(VERSION 3.5)

idf_component_register(
    SRCS "Adafruit_TLV320DAC3100.cpp"
    INCLUDE_DIRS "."
    REQUIRES Adafruit_BusIO
)

project(Adafruit_TLV320_I2S)