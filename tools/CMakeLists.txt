configure_file( cpscpp.in cpscpp @ONLY)
install( FILES ${CMAKE_CURRENT_BINARY_DIR}/cpscpp DESTINATION bin/ PERMISSIONS WORLD_EXECUTE OWNER_EXECUTE GROUP_EXECUTE WORLD_READ GROUP_READ OWNER_READ )
