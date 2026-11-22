idf_component_register(SRCS "rgb_lcd_port.c" 
                        INCLUDE_DIRS "."
                        REQUIRES io_extension esp_lcd ws_gpio ws_i2c io_extension esp_lvgl_adapter esp_lcd_touch_gt911
                        )
