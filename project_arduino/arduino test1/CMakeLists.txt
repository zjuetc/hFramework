cmake_minimum_required(VERSION 2.8)
project(ARoboCoreProject NONE)

include(${HFRAMEWORK_PATH}/hFramework.cmake)

add_hexecutable(myproject main.cpp SparkFunMPU9250-DMP.cpp util/inv_mpu.c util/inv_mpu_dmp_motion_driver.c util/arduino_mpu9250_log.cpp util/arduino_mpu9250_i2c.cpp util/arduino_mpu9250_clk.c)