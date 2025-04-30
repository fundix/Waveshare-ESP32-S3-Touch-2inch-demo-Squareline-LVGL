file(GLOB_RECURSE SRC_UI ${CMAKE_SOURCE_DIR} "ui/*.c")

idf_component_register(SRCS "bsp_qmi8658.c" "main.c" ${SRC_UI}
                    INCLUDE_DIRS "." "ui")
