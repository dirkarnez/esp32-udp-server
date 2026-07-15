idf_component_register(
    SRCS "udp_server.c"
    INCLUDE_DIRS "."
    PRIV_REQUIRES nvs_flash esp_wifi
)
