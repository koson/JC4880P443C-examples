idf_component_register(
    SRCS "main.cpp"
    INCLUDE_DIRS "."
    REQUIRES
        freertos
        nvs_flash
        esp_timer
        driver
        esp_lcd
        esp32_p4_function_ev_board
)
