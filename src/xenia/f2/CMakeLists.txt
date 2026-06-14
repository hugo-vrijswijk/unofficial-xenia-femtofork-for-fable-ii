# src/xenia/f2/CMakeLists.txt - Fable II specific state.

add_library(xenia-f2 STATIC)
xe_platform_sources(xenia-f2 ${CMAKE_CURRENT_SOURCE_DIR})
target_link_libraries(xenia-f2 PUBLIC xenia-base)
xe_target_defaults(xenia-f2)
