cmake_minimum_required(VERSION 3.15)        # Mindestversion von CMake
project(WordleSolver VERSION 1.0 LANGUAGES CXX)  # Projektname und Sprache

# C++-Standard festlegen (z. B. C++17 oder 20)
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

# Haupt-Quellcode-Datei(en)
add_executable(WordleSolver
    src/main.cpp
)

# Wenn du später Bibliotheken nutzt (z. B. curl oder json), kommen die hier hin:
# find_package(CURL REQUIRED)
# target_link_libraries(WordleSolver PRIVATE CURL::libcurl)
