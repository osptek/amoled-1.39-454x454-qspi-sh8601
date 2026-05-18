idf_component_register(SRCS "esp_lcd_sh8601_spi.c" "esp_lcd_sh8601_mipi.c" "esp_lcd_sh8601.c"
                       INCLUDE_DIRS "include"
                       PRIV_INCLUDE_DIRS "priv_include"
                       REQUIRES "esp_lcd" "driver")


