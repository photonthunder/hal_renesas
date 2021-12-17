zephyr_include_directories(${CONFIG_SOC})
message(STATUS "adding Renesas SOC ${CONFIG_SOC}")
zephyr_include_directories(all)
add_subdirectory(all)

