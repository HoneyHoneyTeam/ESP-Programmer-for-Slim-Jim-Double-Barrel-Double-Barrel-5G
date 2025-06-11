This ESP32 programmer is designed for loading firmware and programs onto the ESP32 chipset. There are many versions of ESP32 programmers on the market. While most of them have very similar functionality, it is often uncertain whether a specific programmer will work with particular hardware until it is tested.

To reduce this uncertainty, we have selected this programmer as our first choice for our product line, which includes the ESP32 Marauder Slim Jim, Double Barrel, and Double Barrel 5G. The programmer also comes with a custom-made 4-pin cable.

The following programming tutorial is not exclusive to our programmer. In theory, most ESP32 programmers should work the same way, as long as they use the same chipset and are connected correctly to the ESP32 hardware (3.3V / TX / RX / GND).

Before starting, please download the necessary software and files. In this guide, we will be performing the procedure on Microsoft Windows 11. 


• Flash Download tools from Espressif  
• Four Marauder files from the Marauder GitHub, from the "ESP32 Marauder v4, v6, Kit, Mini" column: 
	○ Bootloader
	○ Partitions
	○ Boot App
	○ Firmware (any version you prefer, preferably the latest one)
• 
1. When all the files are downloaded and ready, run "Flash Download Tools" and set the options as shown in the following two pictures.
2. Connect the ESP32 programmer to the Slim Jim / Double Barrel / Double Barrel 5G via the 4-pin cable: 
a. 3.3V to 3.3V 
b. TX to TX 
c. RX to RX 
d. GND to GND. 
The GPIO pins arrangement is identical between Slim Jim / Double Barrel / Double Barrel 5G (from left to right in the following photos: GND, RX, TX, 3.3V)
3. After that, While holding down the boot button on the back of the device by using a pin or the metal stylus included with the Double Barrel, connect the ESP32 programmer to your PC . This action will put the device into bootloader/downloading mode.
4. Return to Flash Download Tools, select the UART device in the left dottom cornor and click Start. If everything goes as planned, the software will handle the rest in a minute.


- Side notes
	○ If Windows fail the recognise the ESP32 programmer, the programmer's USB driver needs to be installed to allow the procedure to continue. We have provide the USB driver here. 
![image](https://github.com/user-attachments/assets/45a15e3b-9df6-46cd-afe4-a267c8817151)
