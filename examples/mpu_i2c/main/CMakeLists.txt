idf_component_register(SRCS "mpu_i2c.cpp"
                       INCLUDE_DIRS "."
                       REQUIRES "I2Cbus"
                                "MPU"
                       )
