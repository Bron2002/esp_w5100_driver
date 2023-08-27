
idf_component_register(
    SRC_DIRS port/src components/w5100/w5100_esp32/src .
    INCLUDE_DIRS include
    PRIV_INCLUDE_DIRS port/include components/w5100/w5100_esp32/include components/w5100/w5100_esp32/priv_includes
    PRIV_REQUIRES driver esp_eth esp_netif
)