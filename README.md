# USB-GPIO-EXTENDER-T-TOIC

for module with TOIC

file GPIO_TOIC1_Sertik.txt - script on TOIC for module`s firmware

IO1 - PA4 - ADC (0-3.3V)
IO2 - PA2 - Discrete output
IO3 - PA0 - SPI CS
IO4 - PA7 - SPI MOSI
IO5 - PA6 - SPI MISO
IO6 - PA3 - Discrete input (up to 3.3V)
IO7 - PA1 - PWM output with fixed frequency
IO8 - not used
IO9 - PB1 - PWM input (up to 3.3V)
IOx - PA5 - SPI SCK

The demo code supports the following commands:
S - Set output to 1,
R - Set output to 0,
G - Read data from input,
A - Read data from ADC,
K - Send data to SPI and read response,
F - Read data from PWM frequency detector,
I - Read device information.

OpenDevExtTOIC version 1 - script function for Mikrotik Router OS



file GPIO_TOIC2_Sertik.txt - script on TOIC for module`s firmware

IO1 - PA4 - output 1
IO2 - PA2 - output 2
IO3 - PA0 - output 3
IO4 - PA7 - output 4
IO5 - PA6 - output 5

IO6 - PA3 - Input 1
IO7 - PA1 - Input 2
IO8 - PA13 - Input 3
IO9 - PB1 - Input 4
IO10 - Bootloader input contact

IOx - PA5 - Additional input with 10K resistor pull-up to ground
PF0 - controlled LED

The demo code supports the following commands:
~Sx Set output x to 1
~Rx Set output x to 0
~Gx Read current value of input x
~A Read values ​​of all inputs as "xxxxx". Example response "~A11001"
Note: since IO10 is used to jump to the bootloader, it is not used in the program and IO9 signal is displayed again instead.
~Pxxxxх Write values ​​of all outputs as "xxxxx". Example "~P11001"
~B Reboot the module.
~I Request firmware information.
~L test connect and LED


OpenDevExtTOIC version 2 - script function for Mikrotik Router OS


modul USB GPIO EXTENDER T by Open Development Company http://open-dev.ru
https://open-dev.ru/gpio-extender-t

