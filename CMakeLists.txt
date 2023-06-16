cmake_minimum_required(VERSION 3.12)
project(PrintHello)

# Установка стандарта языка C++
set(CMAKE_CXX_STANDARD 11)

# Добавление исходных файлов
set(SOURCES
    main.cpp
    print.cpp
)

# Добавление заголовочного файла
set(HEADERS
    print.hpp
)

# Создание исполняемого файла
add_executable(${PROJECT_NAME} ${SOURCES} ${HEADERS})
