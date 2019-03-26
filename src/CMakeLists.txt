CU_SET_PATH("CMAKE_TEMPLATE_SRC_DIR" "${CMAKE_CURRENT_LIST_DIR}")

AC_ADD_SCRIPT("${CMAKE_TEMPLATE_SRC_DIR}/morph_all_command.cpp")

AC_ADD_SCRIPT_LOADER("morph_all_command" "${CMAKE_TEMPLATE_SRC_DIR}/morph_all_command_loader.h")