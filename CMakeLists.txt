add_library(Navio2 STATIC 
Navio2/ADC_Navio2.cpp
Navio2/Led_Navio2.cpp
Navio2/LSM9DS1.cpp
Navio2/PWM.cpp
Navio2/RCInput_Navio2.cpp
Navio2/RCOutput_Navio2.cpp
Navio2/RGBled.cpp
)
target_include_directories(Navio2 PUBLIC
    ${CMAKE_CURRENT_SOURCE_DIR}/Navio2
)

add_library(Common STATIC 
gpio.cpp
I2Cdev.cpp
MPU9250.cpp
MS5611.cpp
Ublock.cpp
Util.cpp
)
target_include_directories(Common PUBLIC
    ${CMAKE_CURRENT_SOURCE_DIR}/Common
)
