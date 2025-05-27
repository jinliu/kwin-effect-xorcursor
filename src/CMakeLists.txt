kcoreaddons_add_plugin(xorcursor INSTALL_NAMESPACE "kwin/effects/plugins/")

target_sources(xorcursor PRIVATE
    xorcursor.cpp
    main.cpp
)

target_link_libraries(xorcursor
    KF6::CoreAddons
    KWin::kwin
)
