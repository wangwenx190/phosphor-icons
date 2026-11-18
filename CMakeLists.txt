cmake_minimum_required(VERSION 3.25)
project(PhosphorIcons LANGUAGES NONE)
include(GNUInstallDirs)
install(DIRECTORY assets/ DESTINATION "${CMAKE_INSTALL_DATADIR}/phosphor-icons"
    FILES_MATCHING PATTERN "*.svg")
install(FILES LICENSE DESTINATION "${CMAKE_INSTALL_DATADIR}/licenses/phosphor-icons")
