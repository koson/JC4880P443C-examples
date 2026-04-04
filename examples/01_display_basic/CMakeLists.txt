cmake_minimum_required(VERSION 3.16.0)

set(EXTRA_COMPONENT_DIRS 
    "src"
    "../../common_components"
)

include($ENV{IDF_PATH}/tools/cmake/project.cmake)
project(01_display_basic)
