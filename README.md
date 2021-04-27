# smartPot
# DESCRIPTION
This project is about creating a smart pot for plants. The circuit could display on a LCD screen parameters that are important to grow a plant in good conditions.

# DESCRIPTION OF THE CODE
The code First sets up all the sensors (water level sensor, photoresistor, temperature & humidity sensor) and the other component (LED, LCD screen 16x2, and button) that are connected to the Arduino. The LCD first lights up with a Welcoming message which disappears after a few seconds. After that, the screen shows the status of the plant parameters according to the sensors. 
The message says that the plant does not get enough light or does have a too cold environment. All these conditions are based on values that have been chosen through tests to fit the plant's needs as better as possible. If the button is pressed, the state will change from ”status” to ”numbers” which shows the exact values of the sensors. The ledPin port is powered up if the lightValue is too low. If the button is pressed again, the state will go back to the ”status”. 
Once a need for the plant is fulfilled, the corresponding warning status will not be displayed and other warnings will be printed on the screen. If no warnings are in the scope, the screen will print that everything is good.

# LIST OF PARTS NEEDED
1 Arduino UNO Board
1 10 kΩ Potentiometer
1 10 kΩ Resistor
1 LCD Screen 16 X 2
1 kΩ Resistor
1 220 Ω Resistor
1 LED
1 Push Button
1 9V Battery
1 DHT 11 Sensor
1 Water Level Sensor
1 Photoresistor
1 Breadboard
 Jumpers cables Male-Male
 Jumper cables Male-Female
