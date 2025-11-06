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
    ${CMAKE_CURRENT_SOURCE_DIR}
)