cmake_minimum_required(VERSION 3.20.0)
find_package(Zephyr REQUIRED HINTS $ENV{ZEPHYR_BASE})

project(mpu6050_ems)

FILE(GLOB app_sources 
    src/*.c
    src/utilities/*.c
    src/utilities/libpqueue/src/*.c
    src/utilities/circularbuffer/*.c
)

target_sources(app PRIVATE ${app_sources})
