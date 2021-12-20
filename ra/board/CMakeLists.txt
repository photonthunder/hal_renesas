zephyr_include_directories(${CONFIG_SOC})
message(STATUS "adding Renesas Board ${CONFIG_SOC}")
add_subdirectory(${CONFIG_SOC}_ek)

