# Heart-LED
Uses arduino, LCD, push buttons, LEDs, and some sort of canvas.

SUMMARY:
  Eight red LEDs super-glued onto a painting canvas in the shape of a heart (can use something other than a painting canvas; a wooden heart carving maybe?). Three holes were drilled in the wood of the bottom edge of the canvas and pushbuttons were super-glued into each. A rectangle with the dimensions of the LCD screen was cut from the canvas under the LEDs and the LCD screen was glued in position. An arduino nano was soldered onto a prototype circuit board with eight 330 ohm resistors and the eight LEDs soldered to digital pins D5 - D12. 10K ohm resistors were soldered to digital pins D2-D4, as well as the three pushbuttons. The 5V pin supplied power to the pushbuttons and the LCD screen. The ground pin was connected to the pushbuttons, LEDs, and LCD screen. Analog pins A4 and A5 were connected to the SDA and SCL of the LCD screen, respectively. The code written using the Arduino IDE was uploaded to the arduino nano. The board was powered using its mini-B USB port.
  This version is one of many prototypes I will (probably) make. If you want to make this same project, I suggest using a wooden heart carving or a painted canvas (something more than a blank painting canvas).

CONTENTS:
This repository contains the materials used, circuit schematic, assembly instructions, and code file.

INSPIRATION:
I created this in February of 2018 and thought I would upload it here! With Valentine's Day approaching and minimal gift ideas for my girlfriend, I found an old painting canvas lying around and thought I could do something with it. I had plenty of electronic components lying around and began brainstorming some ideas. I thought a red heart made out of LEDs would suffice! I wanted to make multiple effects to choose from so I needed to add in some pushbuttons and a menu on a screen.
