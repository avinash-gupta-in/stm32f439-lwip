Basic lwIP based project generated using CubeMX GUI
This code only initializes the inbuilt Ethernet peripheral
STM32F429/STM32F439 chip, the PHY chip LAN8792, FreeRTOS
and lwIP. After this the board can be connected to Ethernet.
Then we can use ping command to test the connectivity.
However this code does not contains any other communication
code like TCP/UDP server or client code but it can be used
as a base for such codes and in latter lectures I will show
you how to write such codes.

This codes uses static IP for this board (no DHCP). The
IP address can be changed using the CubeMX GUI (load .ioc file)
I have used the IP 192.168.1.120
You can confirm the same by going through the implementation
of the function.
 
void MX_LWIP_Init(void)
 
Hardware: STM32F439 Nucleo Board
 
This code is a part of my PAID course here at
https://www.stm32tutorials.com
Author: Avinash Gupta

![STM32F439 Board Running lwIP and FreeRTOS](https://www.extremeelectronics.co.in/github/stm32-lwip/stm32f439_nucleo.jpg)
