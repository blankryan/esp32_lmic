#CMakeLists Library

idf_component_register(
    SRCS "aes.c" "hal.c" "lmic.c" "oslmic.c"
    INCLUDE_DIRS "include"
    COMPONENT_REQUIRES
        nvs_flash
        mbedtls
        driver
        esp_event
        esp_timer
)
