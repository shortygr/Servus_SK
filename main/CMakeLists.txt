idf_component_register(
    SRCS "main.c"
    INCLUDE_DIRS "."
    REQUIRES fonts gui_paint image io_extension sd ws_i2c usart ws_gpio rgb_lcd_port
    WHOLE_ARCHIVE
    )
    
idf_component_get_property(lvgl_lib lvgl__lvgl COMPONENT_LIB)
target_compile_options(${lvgl_lib} PRIVATE -Wno-format) 