cmake_minimum_required(VERSION 3.18)

project(Hello LANGUAGES CXX)

add_executable(hello helloWorld.cpp)

#Durante a instalação, escolha a opção para adicionar o CMake ao PATH do sistema (opção "Add CMake to the system PATH for all users" ou semelhante).