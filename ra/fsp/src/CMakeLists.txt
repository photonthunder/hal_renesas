add_subdirectory(bsp)
add_subdirectory_ifdef(CONFIG_RENESAS_DRIVER_AGT r_agt)
add_subdirectory_ifdef(CONFIG_RENESAS_DRIVER_FLASH_LP r_flash_lp)
add_subdirectory_ifdef(CONFIG_RENESAS_DRIVER_GPT r_gpt)
add_subdirectory_ifdef(CONFIG_RENESAS_DRIVER_ICU r_icu)
add_subdirectory_ifdef(CONFIG_RENESAS_DRIVER_IOPORT r_ioport)