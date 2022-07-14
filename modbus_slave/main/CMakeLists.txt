set(PROJECT_NAME "modbus_slave")

idf_component_register(SRCS "slave.c" "modbus_params.c"
                    INCLUDE_DIRS ".")
