# STM32 Button Game
This is button game implemented on STM32F4 Nucleo Board connected with 5-tact switches

# What code does?

In this project, we have to press 16 times these 5 buttons randomly. And which button is pressed will be recorded in buffer. Once the 16 times button pressed completed, the sequence of button pressed will be printed on serial terminal. Here we're using USART2 of STM32F4 Nucleo Board with baud rate of 115200.

# How to connect swicthes?

<p> #SW1 --> PB1 </p>
<p> #SW2 --> PB2 </p>
<p> #SW3 --> PB3 </p>
<p> #SW4 --> PB4 </p>
<p> #SW5 --> PB5 </p>

#In code, the GPIO input pins are pulled high. This means when we press the switch, it generates Logic LOW (pulled to GND). Please find an attached images or your reference in the directory shared
