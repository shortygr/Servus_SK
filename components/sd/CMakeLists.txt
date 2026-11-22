idf_component_register(SRCS "sd.c"  
                        INCLUDE_DIRS "."
                        REQUIRES driver fatfs ws_i2c ws_gpio io_extension
                    )
