# This file was automatically generated for projects
# without default 'CMakeLists.txt' file.

set(srcs 
    main.cpp queue.cpp)

idf_component_register(SRCS "main.cpp" "${srcs}"
                    INCLUDE_DIRS "" "$ENV{IDF_PATH}/components/driver/gpio/include" "$ENV{IDF_PATH}/components/esp_timer/include")
