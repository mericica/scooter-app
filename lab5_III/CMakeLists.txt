cmake_minimum_required(VERSION 3.24)
project(lab5_III)

set(CMAKE_CXX_STANDARD 14)

include_directories(lab5_II/Controller)
include_directories(lab5_II/Domain)
include_directories(lab5_II/Repository)
include_directories(lab5_II/Tests)
include_directories(lab5_II/UI)

add_executable(lab5_III
        lab5_II/Controller/Controller.cpp
        lab5_II/Controller/Controller.h
        lab5_II/Domain/Customer.cpp
        lab5_II/Domain/Customer.h
        lab5_II/Domain/Scooter.cpp
        lab5_II/Domain/Scooter.h
        lab5_II/Repository/CustomerFileRepo.cpp
        lab5_II/Repository/CustomerFileRepo.h
        lab5_II/Repository/FileRepo.h
        lab5_II/Repository/MemoryRepo.cpp
        lab5_II/Repository/MemoryRepo.h
        lab5_II/Repository/Repo.h
        lab5_II/Repository/ScooterFileRepo.cpp
        lab5_II/Repository/ScooterFileRepo.h
        lab5_II/Tests/tests.cpp
        lab5_II/Tests/tests.h
        lab5_II/UI/UI.cpp
        lab5_II/UI/UI.h
        lab5_II/main.cpp)
