cmake_minimum_required(VERSION 3.22)
project(ee205_lab_08d_animal_farm_1_to_clion)

set(CMAKE_CXX_STANDARD 14)

add_executable(
        ee205_lab_08d_animal_farm_1_to_clion
        main.c
        addCats.c addCats.h
        catDatabase.c catDatabase.h
        config.h
        deleteCats.c deleteCats.h
        reportCats.c reportCats.h
        updateCats.c updateCats.h
        validate.c validate.h)
