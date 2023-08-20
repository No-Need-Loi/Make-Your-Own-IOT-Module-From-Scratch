# Make-Your-Own-IOT-Module-From-Scratch

![Screenshot (1748)](https://github.com/No-Need-Loi/Make-Your-Own-IOT-Module-From-Scratch/assets/142481076/8c80d9f4-45a9-4990-886f-cc4bcaf36504)


The ESP8266 is a high-performance, low-cost board developed by Espressif Systems. This board has gained popularity in the hardware community. This can be attributed to the excellent features and benefits this board offers. Also, one of the reasons it gained popularity is that it enables users to use the Arduino IDE in programming it.

The ESP8266 board is a microcontroller that allows users to use the Arduino IDE for its programming. As an SoC incorporated with an IP or TCP protocol stack, this board can offer access to any Wi-FI network. ESP8266 is mainly designed for the development of IoT applications.

![Screenshot (1746)](https://github.com/No-Need-Loi/Make-Your-Own-IOT-Module-From-Scratch/assets/142481076/3c30e0e8-c9f7-4fe9-9dcf-5191988c43b4)

This project contains PCB and which was made with the help of JLCPCB

JLCPCB has upgraded the via-in-pad process of all 6-20 layer PCBs for free and provides free ENIG to make PCB products more stable and reliable. It is worth mentioning that due to large-scale production capabilities, JLCPCB is able to reduce the cost, allowing everyone to truly enjoy the benefits of the JLCPCB advanced fabrication. Here at JLCPCB, you can also get 1-8 layer PCBs at only $2

![FWII4IJLL9GI260](https://github.com/No-Need-Loi/Make-Your-Own-IOT-Module-From-Scratch/assets/142481076/67b62e19-8f9f-49d0-ad29-23b9f57c6543)

Go to JLCPCB website and create a free account.  

Register and Login using Google Account is also possible.

![FEP2OKBLL9GI263](https://github.com/No-Need-Loi/Make-Your-Own-IOT-Module-From-Scratch/assets/142481076/ea625100-2640-442f-abd8-6b5d6f98d9c7)

Step 2 – Upload Gerber File
Once you have successfully created an account, Click on “Quote Now” and upload your Gerber File.

![FWBKDVKLL9GI262](https://github.com/No-Need-Loi/Make-Your-Own-IOT-Module-From-Scratch/assets/142481076/9ceb21da-126e-4870-9ede-93ede0a4252d)

Gerber File contains information about your PCB such as PCB layout information, Layer information, spacing information, tracks to name a few.

![FTC3JQDLL9GI261](https://github.com/No-Need-Loi/Make-Your-Own-IOT-Module-From-Scratch/assets/142481076/1d2a8076-225b-4efd-bbaf-337cefa3a48c)

Step 3 – Preview the File
Once the Gerber file is uploaded, it will show you a preview of your circuit board.

Make sure this is the PCB Layout of the board you want.

![FYI7NXZLL9GI25W](https://github.com/No-Need-Loi/Make-Your-Own-IOT-Module-From-Scratch/assets/142481076/4d0a9385-786c-4d1c-8d5f-b7cd9ae1626a)

Step 4 – Choose Necessary PCB Options

Below the PCB preview, you will see so many options such as PCB Quantity, Texture, Thickness, Color etc. Choose all that are necessary for you. 

It enables the connection of the internet to different applications of embedded systems. ESP8266 was designed in such a way that it offer support to IP or TCP capability. Also, the ESP8266 board can function as a standalone or a slave application. If this board is integrated as a standalone application, it functions as a microcontroller. However, if it runs as a slave, users can integrated it as a Wi-Fi adaptor.

To allow communication between the microcontroller and the ESP8266 Wi-Fi module, some AT commands are required. Therefore, ESP8266 comes with AT commands software which enables it to offer the functionalities of the Arduino Wi-Fi.

Before we continue with the ESP8266 PCB design, you should comprehend the significance of the circuit diagram. A circuit diagram needs to be designed with all the necessary connections and components. This will make the ESP8266 PCB design process easier. So, what are the components needed for the ESP8266 PCB design? Below are all the components integrated in designing the circuit of the ESP8266 PCB board:

Female Headers (a few strips)
Two Way Slide Switch
ESP8266 WiFi Module (ESP-01)
Push Button
2.2 KΩ Resistor (1/4 Watt)
1 KΩ Resistor (1/4 Watt)
100 nF Capacitor
After you have designed your circuit diagram, you need a circuit design. In this phase, you need to get the pin configuration of the ESP8266. For instance, the ESP8266ESP-01 comes with 8 pins. These pins include GND, GPIOO, CH_PD, VCC, TX, GPIO2, RX, and RST.

![Screenshot (1751)](https://github.com/No-Need-Loi/Make-Your-Own-IOT-Module-From-Scratch/assets/142481076/a7034ca2-3766-46ee-a366-6c32e3fae6fb)

As regards the circuit design, the CH_PCD and VCC pins of the ESP8266 are usually connected to power supply header’s VCC terminal. The GND pin is usually connected to the GND terminal. There is a 100 nF eramic disc capacitor between the GND female headers and the VCC.

The RST pin means Reset. This pin is usually linked to an end of a push button. Then the designer connects the other head of the button to GND.

It is important to know where the GPIO2 pin is connected. This pin is directly connected to any of the terminals GPIO female header while the other pin end is linked to GND.

The communication pins which include RX and TX are the next pins to connect. While the TX pin is directly linked to the communication female header’s TX terminal, the RX pin is linked via a level converter that comprises a 2.2K Ω and a 1K Ω resistor.

The introduction of the ESP8266 board has made it possible for developers and makers to create projects that are internet enables at a very low cost. Also, the popularity of the ESP8266 board led to the development of commercial boards such as Adafruit’s Huzzah, NodeMCU, and WeMos D1.

![Screenshot (1755)](https://github.com/No-Need-Loi/Make-Your-Own-IOT-Module-From-Scratch/assets/142481076/a48647a7-da89-4baf-bcd6-f0f858e50eb8)

ESP8266 board is integrated with RF transmitter, RF balun, analog transmitter, and power modules among others. The main benefit of the ESP8266 board is the its embedded wireless technology. This board requires no peripherals or shields. Also, it offers additional benefits like great processing power and speed. This board allows users to use the Arduino IDE to program it.

![Screenshot (1756)](https://github.com/No-Need-Loi/Make-Your-Own-IOT-Module-From-Scratch/assets/142481076/aa6792c6-94ab-460c-8fb1-ae0f21654248)

The 32-bit processor featuring 16-bit instructions powers the ESP8266. Because of the Harvard architecture, instruction memory as well as data memory remains entirely independent.

The Read-Only Memory (ROM) of the ESP8266 contains a initial phase boot loader and several library code. The remaining code needs to be kept in an exterior flash memory (offers just data serial access – instead of considering the individual bytes, this user writes or reads large bytes inside the address spaces in a serial manner).

The quantity of flash memory that is readily available can differ depending on the ESP8266.
The ESP8266 contains some GPIO pins that can be used to “control” the external sensors, much like all other microcontrollers.
Just 11 of the ESP8266’s Seventeen GPIO pins are usable (among the 17 pins, six are utilized for communications with flash on-board memory chip). Another option is the analog input (which helps in converting a level of voltage into a form of digital value which could be stored as well as processed in ESP8266).
Also it features WiFi connectivity, allowing you to connect the ESP8266 to any WiFi network, access the internet, run a web service, and allow your smartphone to connect, among other things.
The ability to be programmed like all other microcontrollers, especially any type of Arduino, is another characteristic of the ESP8266.

The power pins

![Screenshot (1757)](https://github.com/No-Need-Loi/Make-Your-Own-IOT-Module-From-Scratch/assets/142481076/a83c610e-d02e-4ea3-bd3f-774406741efb)


The power pins are four in number. Three pins of 3.3V and the VIN pin.

The NodeMCU/ESP8266 as well as its peripherals can be powered directly through VIN. The NodeMCU module’s internal regulator regulates the power provided on VIN; you also can supply 5V managed to this VIN pin.
An onboard voltage regulator’s 3.3V pins, which may be utilized to power external components, are its output.
GND pins
You can refer to this as ground pins of ESP8266

I2C Pins 
The I2C sensors and accessories are connected by use of pins. The I2C Master as well as Slave protocols are both supported. Programmatically implemented I2C interface function is possible, and the maximum clock frequency equals 100 kHz. It ought to be remembered that the frequency of the I2C clock should be greater than the slave device’s slowest clock frequencies.

GPIO Pins 
The ESP8266 includes seventeen GPIO pins that may be dynamically allocated to perform tasks including I2C, I2S, PWM, UART, IR Remote Controls, LED Light, as well as Button. Each GPIO with digital capability can be adjusted to a high impedance, internal pull-up, and internal pull-down. It may also be configured to level-trigger or edge-trigger when setup as an input to produce CPU interrupts it.

ADC Channel
The 10-bit precision ADC is built within the ESP8266. ADC can be utilized to implement the two tasks. These include checking the TOUT pin’s input voltage and the power voltage supply of the VDD3P3 pin. These cannot, however, be put into action simultaneously.

UART Pins
The ESP8266 includes two asynchronous UART interfaces (UART1 and UART0) that support RS485 and RS232 communication. Also, it can also communicate at about 4.5 Mbps.

You can utilize the TXD0, RST0, RXD0 and CTS0 pins on UART0 to communicate. UART1 pin only has a data transmitting signal, hence that’s why it’s typically used in printing logs

First of all, we need to recollect the Pin Configuration of the ESP8266 WiFi Module. The ESP8266 ESP-01 variant has 8 pins, namely: VCC, GND, RX, TX, GPIO0, GPIO2, RST and CH_PD. The pin description is already mentioned in the earlier tutorials.

Coming to the design of the circuit, the VCC and CH_PD pins of the Module are connected to the VCC terminal of the Power Supply header, while the GND pin is connected to GND terminal.

A 100 nF ceramic disc capacitor is connected between the VCC and GND female headers.

The RST (reset) pin is connected to one end of a push button and the other end of the button is connected to GND.

![Screenshot (1758)](https://github.com/No-Need-Loi/Make-Your-Own-IOT-Module-From-Scratch/assets/142481076/d253540d-d30f-4e87-89e6-9ac70f16d9a3)


GPIO2 is connected directly to one of the terminals in the female header for GPIO. The GPIO0 pin is connected to the center terminal of a two way slide switch. One end of the switch is connected to the second terminal of the female header for GPIO while the other end is connected to GND.

Next is the communication pins i.e. TX and RX. The TX pin of the ESP8266 WiFi Module is directly connected to the TX terminal of the communication female header. The RX pin on the other hand, is connected through a level converter consisting of a 1KΩ and a 2.2KΩ resistor.

We will not use any USB-to-UART chip like CP2102, rather we will program the device using external FTDI. By removing the extra chips and using the low-power LDOs will reduce the power consumption and makes the device small-sized. Thus the device can operate with a small Lithium-Ion Battery and charge either using USB or Solar Power. You can also use ESP8285 as an alternative and most of the points discussed here will still be the same.

Working of PCB for ESP8266 WiFi Module
After assembling the components, connect 3.3V supply to the VCC and GND pins on the board. If you want to program the ESP8266 or flash the firmware onto it, slide the switch to Programming Mode position and press the Reset button once.WiFi module is based on ESP8266 Integrated Chip from Espressif, offering a complete WiFi networking solution. It can be used either to host the applications or to offload all WiFi networking functions from another application processor. Rich interface (GPIO, SPI, SDIO, I2C) options gives this board potential to be a standalone MCU with WiFi capability for wide range of applications.

![Screenshot (1759)](https://github.com/No-Need-Loi/Make-Your-Own-IOT-Module-From-Scratch/assets/142481076/0f12b546-0ff6-4044-bbd2-eb35938b26f7)

This project contains PCB and which was made with the help of JLCPCB

JLCPCB has upgraded the via-in-pad process of all 6-20 layer PCBs for free and provides free ENIG to make PCB products more stable and reliable. It is worth mentioning that due to large-scale production capabilities, JLCPCB is able to reduce the cost, allowing everyone to truly enjoy the benefits of the JLCPCB advanced fabrication. Here at JLCPCB, you can also get 1-8 layer PCBs at only $2

Go to JLCPCB website and create a free account.  

Register and Login using Google Account is also possible.

Step 2 – Upload Gerber File
Once you have successfully created an account, Click on “Quote Now” and upload your Gerber File.


Gerber File contains information about your PCB such as PCB layout information, Layer information, spacing information, tracks to name a few.

Step 3 – Preview the File
Once the Gerber file is uploaded, it will show you a preview of your circuit board.

Make sure this is the PCB Layout of the board you want.

Step 4 – Choose Necessary PCB Options

Below the PCB preview, you will see so many options such as PCB Quantity, Texture, Thickness, Color etc. Choose all that are necessary for you. 

During development stage, you need a software development kit (SDK), like Arduino IDE, with ESP8266 Board Manager and supporting libraries, or the newer PlatformIO IDE, for writing the software.

![Screenshot (1752)](https://github.com/No-Need-Loi/Make-Your-Own-IOT-Module-From-Scratch/assets/142481076/843f13aa-9bf8-4494-84da-3a171e1072e7)

Software code is flashed into ESP8266 chip using the built-in serial TTL-to-USB adaptor (sometimes called USB-to-UART bridge). For flashing any new software, ESP8266 chip must be rebooted in flash mode, and USB signals from the computer must be converted to serial UART signals and transferred to the chip using Rx0 and Tx0 pins (GPIO3 and GPIO1).
On NodeMCU board, support circuitry automatically handles all these things in a seamless manner. This makes NodeMCU or similar board, like WemosD1 Mini, popular among hobbyists. Note that, Reset and Flash buttons are also built onto NodeMCU board to help in case auto-loading fails.
﻿
Deployment/production stage
During this stage, only ESP8266 chip is required in the final product.

The issue now is to figure out how to use ESP8266-12E/F (or ESP-12E/F) chip and still be able to load the code and develop the software without NodeMCU or similar board. For that, first we need to know the physical size, working, booting and flashing process of ESP-12E/F chip in detail.

ESP-12E is a miniature Wi-Fi module present in the market and is used for establishing a wireless network connection for a microcontroller or processor. The core of ESP-12E is ESP8266EX, which is a high integration wireless SoC (System on Chip). It features the ability to embed Wi-Fi capabilities to systems or to function as a standalone application. It is a low-cost solution for developing IoT applications.

ESP8266-12F is an enhanced version of ESP8266-12E that has improved peripheral circuit, enhanced impedance matching, the signal output is better, stable with anti-jamming ability.

Frequency Range: 2.412 – 2.484 GHz
Serial Transmission: 110 – 921600 bps, TCP Client 5
SDIO 2.0, SPI, and UART Interface available
PWM available
One ADC channel is available
Programmable GPIO available
Wireless Network Type: STA / AP / STA + AP
Security Type: WEP / WPA-PSK / WPA2-PSK
Encryption Type: WEP64 / WEP128 / TKIP / AES
Network Protocol: IPv4, TCP / UDP / FTP / HTTP
Operating Voltage: 3.3V
Maximum current allowed to draw per pin: 15mA
Power down leakage current of < 10uA
Integrated low power 32-bit MCU
Onboard PCB Antenna
Wake up and transmit packets in < 2ms
Standby power consumption of < 1.0mW
Operating Temperature: -40ºC to +125 ºC

![Screenshot (1751)](https://github.com/No-Need-Loi/Make-Your-Own-IOT-Module-From-Scratch/assets/142481076/ace4d488-d8a8-44cd-9a13-818a31aff6b6)

Programming the ESP8266 Chip
The above circuit has an automatic programmer. You just need an FTDI Module to program the raw ESP chip. There is no need for manual programming or pressing and releasing the push buttons. The programming process is automatic and handled by two switches (FLS and RST), two BC547 transistors (Q1 and Q2), and a few other components.
