# sx1278_stm32_lib
Library for using sx1278 with stm32

Library provides basic funcionality to configure, send and receive.

User should provides:
- delay.h & delay.c with basic delay functionality
- sx1278_pin.h with definition of pin to be used
- spi.c & spi.h with spi config and w/r access
- std_peripheral library for the selected micro
