# GoodLight_BadUSB
Project under "Embedded System Lab Training SS_2018" course, RCSE

### Breadboard
<img width="95%" src="GoodLight_BadUSB_breadoard.png">

### Required Components
- Arduino Uno Board with USB connector
- Breadboard
- LCD Screen (compatible with Hitachi HD44780 driver)
- Photocell(LDR)
- Buzzer
- Red LED
- 10k ohm Potentiometer
- 220 ohm resistor x 4
- Jumper wires x 30

### Schematic
<img width="95%" src="GoodLight_BadUSB_schematic.png">

### Functional Requirements
- LDR should continuously sense the intensity of the surrounding Light.
- If the surrounding light intensity is High:
  - Display Message on LCD Screen "Light Intensity is OK."
- If the surrounding light intensity is Low:
  - Display Message on LCD Screen "Light Intensity is Low. Please turn on Light."
  - Wait for 5 mins so that user can turn on the light. 
  - If person doesn't switch on the Light:
    - Perform the action i.e. play the Buzzer sound.
  - If user turns on the light:
    - Check the Light Intensity again and display corresponding message.


### References
https://www.arduino.cc/en/Tutorial/HelloWorld 
