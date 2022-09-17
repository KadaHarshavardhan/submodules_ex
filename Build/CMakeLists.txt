add_executable(${PROJECT_NAME} 
    ../Sources/main.c
)

target_link_libraries(${PROJECT_NAME}
    LINK_PUBLIC
    Sources
)