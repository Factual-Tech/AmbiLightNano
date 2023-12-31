# AmbiLight with an Arduino Nano

## Required Hardware

<img src="images/led_strip.png" alt="Led strip">
- WS2812 5V Led strip (60leds/meter)

<br>
<br>

<img src="images/nano.png" alt="Arduino Nano">
- Arduino Nano (or other microcontroller, Nano is the best option)

<br>
<br>

<img src="images/female_connector.png" alt="Female Connector">
- Female connector

<br>
<br>

<img src="images/ribbon_cables.png" alt="Cables">
- 3 Cables

<br>
<br>

<img src="images/power_supply.png" alt="5V Power Supply">
- 5V Power supply, the maximum wattage needs to be chosen based on the lenght of strip and the wattage for meter

<br>
<br>

In my case i used 60leds/meter for a absoption of 18W/m for a total of 2.5 meter, so 18*2.5 = 45W, so i needed a 10A power supply (45W/5V = 9A)

<br>
<br>

## Schematic

<img src="images/schematic.png" alt="Schematic">

<br>
<br>

## Arduino Program

- Download Adalight WS2812 from github page : https://github.com/Wifsimster/adalight_ws2812

<img src="images/1.png" alt="Code to download">

<br>

- Open the code in Arduino IDE
- Edit the parameters to be compiant to your schematic

<br>

<img src="images/2.png" alt="Settings">

<br>

- Upload to Arduino selecting "Nano" and the right COM port

<br>
<br>

## PC setup

- Download Prismatik from github: https://github.com/psieg/Lightpack/releases
