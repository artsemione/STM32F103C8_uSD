# STM32F103C8_uSD

Writing operations on a SD card for dataloggers, using a STM32F103 microcontroller and a Micro SD Card Adapter.

Code generated from STM Cube MX.
IDE: Keil uVision V5

Code Guide to the project:  http://narodstream.ru/stm-urok-88-sd-spi-fatfs-chast-1/
How to Use MMC/SDC:         http://elm-chan.org/docs/mmc/mmc_e.html

#Microcontroller Pin Configuration:
  
 PB15: SPI2 MOSI.
 PB14: SPI2 MISO.
 PB13: SPI2 SCK.
 PB12: Chip Select (*User Define).
    
#MicroSD Card Adapter Pins:
  
   Adapter:        STM32F103C8:
    CS      <--->   PB12 
    SCK     <--->   PB13
    MOSI    <--->   PB15
    MISO    <--->   PB14
    VCC     <--->   5V  
    GND     <--->   GND




