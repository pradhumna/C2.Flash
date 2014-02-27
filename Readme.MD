Implement Silabs C2 flash programming protocol via Arduino and EFM32ZG STK-3200 boards.
See
https://www.silabs.com/Support%20Documents/TechnicalDocs/an127.pdf
and
http://akb77.com/g/silabs/jump-to-silabs-step-1/
for details

1. Upload C2_Flash.pde sketch to Arduino
   Upload C2.Flash.bin to EFM32ZG STK-3200
2. Connect
    Target          Arduino        Atmel       EFM32ZG STK-3200
        C2CK      - digital pin 5 (PortD 5)      PC0
        C2D       - digital pin 6 (PortD 6)      PC1
        GND       - GND                          GND
3. Start program C2.Flash.exe (need .NET 2.0)