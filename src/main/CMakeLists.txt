set(srcs "hello_world_main.c")

idf_component_register(SRCS "${srcs}"
                       INCLUDE_DIRS "."
                       EMBED_TXTFILES "${test_bin}")
