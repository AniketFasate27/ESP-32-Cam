# ESP-32-Cam

The board is powered by an ESP32-S SoC from Espressif, a powerful, programmable MCU with out-of-the-box WIFI and Bluetooth.
It’s the cheapest (around $7) ESP32 dev board that offers an onboard camera module,   MicroSD card support, and 4MB PSRAM at the same time.
Adding an external wifi antenna for signal boosting requires extra soldering work.
The board does not have a conventional USB port, you will have to use either an FTDI programmer, or an add-on HAT, or an Arduino UNO along with the Arduino IDE/ESP-IDF 
DEV tools to upload codes to it.
Being a low-cost board in a small enough form factor has made it extremely popular for many IoT and machine vision applications.
The outdated spec sheet and many tutorial pages say that the ESP32-CAM only supports two camera modules (OV2640 & OV7670), 
while in fact you can use many cameras with it, simply scroll down for more details.
