idf_component_register(SRCS "mpu_spi.cpp"
                       INCLUDE_DIRS "."
                       REQUIRES "MPU"
                                "I2Cbus"
                                "SPIbus"
                       )
