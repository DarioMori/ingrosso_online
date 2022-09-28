cmake_minimum_required(VERSION 3.21)
project(ingrosso_online)

set(CMAKE_CXX_STANDARD 14)

add_executable(ingrosso_online main.cpp users.h clienti.h providers.h magazzino.h carrello.h products.h categorie.h users.cpp clienti.cpp providers.cpp magazzino.cpp carrello.cpp products.cpp categorie.cpp)
