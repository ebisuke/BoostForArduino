cmake_minimum_required(VERSION 3.5)


set(INCLUDEDIRS
        src
        )


idf_component_register(INCLUDE_DIRS ${INCLUDEDIRS})
