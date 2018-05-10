cmake_minimum_required(VERSION 3.8)

set(CMAKE_MODULE_PATH ${CMAKE_CURRENT_LIST_DIR}/KotlinCMakeModule)

project(hello_world Kotlin)

konanc_executable(
    NAME hello
    SOURCES src/main/kotlin/hello.kt)

