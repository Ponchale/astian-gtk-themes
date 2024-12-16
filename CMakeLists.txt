cmake_minimum_required(VERSION 3.5)
project(gtk-theme)
install(DIRECTORY Astian DESTINATION ${CMAKE_INSTALL_PREFIX}/share/themes)
install(DIRECTORY Astian-light DESTINATION ${CMAKE_INSTALL_PREFIX}/share/themes)
install(DIRECTORY Astian-dark DESTINATION ${CMAKE_INSTALL_PREFIX}/share/themes)
    
