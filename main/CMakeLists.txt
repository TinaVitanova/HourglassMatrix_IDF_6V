idf_component_register(SRCS "hourglass_timer.c" "mpu_6050.c" "dot_matrix.c" 
                       PRIV_REQUIRES spi_flash
                       REQUIRES driver esp_timer esp_driver_spi esp_driver_i2c esp_driver_gpio
                       INCLUDE_DIRS "")
