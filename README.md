# Tesla prototype

This is a private project developed with Armour grade https://armourgrade.com/.

## Requirements

 Software: 

 * Arduino IDE https://www.arduino.cc/en/software

 Hardware: 

 1. Arduino OLED display
 2. LOLIN WROOOM ESP32 LITE microcontroller 
 3. Button 
 4. Lithium Polymer Rechargable Battery 50mah 3.7V
    

## Hardware wiring 

   Arduino OLED display to the microcontroler:
   
   * GND -> GND 
   * VCC -> VCC
   * SCL -> GPIO4 
   * SDA -> GPIO5
   


 Button to the microcontroler:
  
  * One pin of the button is connected via 4k7 resistor to VCC (pull-up resistor) and also to GPIO32 (it must be an RTC pin because of deep sleep wakeup) of the microcontroller 
   
  * The other pin is connected to the GND of the microcontroller 



## Installation

1. Clone the git repository
2. Upload the code to the microcontroller via Arduino IDE


## Demonstration
![tesla_prototype](https://github.com/alex64a/Tesla_prototype/assets/50616697/405fe152-00d6-461d-8353-3a5485d6b956)

## Credits

Srdjan Srdić, Ninoslav Srdić

