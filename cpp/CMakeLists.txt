project(custom_lib_rust_bindings)
add_library(custom_lib_rust_bindings custom_lib_rust_bindings.cpp)

target_include_directories(custom_lib_rust_bindings PRIVATE
        include
)

target_link_libraries(custom_lib_rust_bindings PRIVATE
        custom_lib
)

