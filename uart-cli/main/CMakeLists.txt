idf_component_register(
    SRCS "uart-cli.c"
    INCLUDE_DIRS "."
    REQUIRES esp_driver_gpio esp_driver_uart led_strip
)
