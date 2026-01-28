if (DEFINED ESP_PLATFORM)
    idf_component_register(
        SRCS "Adafruit_TLV320DAC3100.cpp"
        INCLUDE_DIRS "."
        REQUIRES adafruit_busio
    )
endif()