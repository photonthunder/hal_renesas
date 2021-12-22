zephyr_include_directories(${CONFIG_SOC}_ek)
message(STATUS "adding Renesas Board ${CONFIG_SOC}")
add_subdirectory(${CONFIG_SOC}_ek)

