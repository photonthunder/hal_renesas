zephyr_sources_ifdef(CONFIG_RENESAS_BSP_DELAY bsp_delay.c)
zephyr_sources_ifdef(CONFIG_RENESAS_BSP_IRQ bsp_irq.c)
zephyr_sources_ifdef(CONFIG_RENESAS_BSP_REG_PROT bsp_register_protection.c)
zephyr_sources_ifdef(CONFIG_RENESAS_BSP_CLOCKS bsp_clocks.c)
zephyr_sources_ifdef(CONFIG_RENESAS_BSP_COMMON bsp_common.c)