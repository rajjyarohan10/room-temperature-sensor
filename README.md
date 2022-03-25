# room-temperature-sensor
> Using an Arduino to sense the room temperature using a thermistor

## Hardware
For this project, I used the following items for the hardware 
1. Breadboard 
2. Wires 
3. Arduino Uno Raspberry Pi
4. LEDs 
5. Thermistor 

## Software 
The actual programming of the LED lights takes place in the form of C++ code in the Arduino IDE. The thermistor senses the appropriate readings and the *LiquidCrystal* displays the calculated temperature. 

In this code, `setup()` and `loop()` are the main functions where the programs are written.

`loop()` continuiously loops and displays new values calculated by the thermistor.

`setup()` initializes the **Serial**

## Pictures 
> Here are some pictures of the ***room-temperature-sensor*** in action.

![Image1, the working prototype](/assets/images/tux.png)
