# Edit following two lines to set component requirements (see docs)
set(COMPONENT_REQUIRES )
set(COMPONENT_PRIV_REQUIRES )

set(COMPONENT_SRCS "main.c" "ADC.c" "PWM.c" "timer.c" "UART.c")
#set(COMPONENT_SRCS "main.c")
set(COMPONENT_ADD_INCLUDEDIRS "include")

register_component()
