set(srcs "src/esp_nettap.c")
set(include "include")

idf_component_register(SRCS ${srcs}
                    INCLUDE_DIRS ${include}
                    REQUIRES esp_netif)
