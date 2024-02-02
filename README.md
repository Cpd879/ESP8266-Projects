# ESP8266 Projects

Welcome to the ESP8266 Projects repository! This collection of projects demonstrates various functionalities and applications using the ESP8266 microcontroller with the Arduino framework.

## Project List

1. **AllBlank: [ALLBLANK]**
   - *Description*: Blank
   - *Components*: N/A
   - *Wiring*: N/A
   - *Usage*: Turns NodeMCU To Blank 

2. **BlinkingLED: [BLINKINGLED]**
   - *Description*: Blinks The In-Built LED
   - *Components*: N/A
   - *Wiring*: N/A
   - *Usage*: Blinks The Inbuilt LED.

3. **BlinkingLEDUsingBlynkIOT: [BLINKINGLEDUSINGBLYNKIOT]**
   - *Description*: Blinks The In-Built LED Using Blynk IOT.
   - *Components*: Go to Blynk IOT. Follow The Instructions In The Code.
   - *Wiring*: N/A
   - *Usage*: Blinks The Inbuilt LED.

4. **WebServerCodeSTA: [WEBSERVERCODESTA]**
   - *Description*: Blinks The Inbuilt LED Using WebServer. Video Link - https://www.youtube.com/watch?v=pqaaPSRiYec @BINARYUPDATES
   - *Components*: Server Is Hosted On NodeMCU's IP.
   - *Wiring*: N/A
   - *Usage*: Blinks The Inbuilt LED. 

5. **WebServerCodeAPM: [WEBSERVERCODEAPM]**
   - *Description*: Blinks The Inbuilt LED Using WebServer. Video Link - https://www.youtube.com/watch?v=U1lCUFLpxiQ @BINARYUPDATES
   - *Components*: Server Is Hosted On NodeMCU's IP. (Note - You Have To Connect To The ESP8266's Network First!)
   - *Wiring*: N/A
   - *Usage*: Blinks The Inbuilt LED. 

6. **SOSLight: [SOSLIGHT]**
   - *Description*: Blinks The Inbuilt/External LED In An SOS Pattern.
   - *Components*: LED, 2 Jumper Wires, Resistor, Breadboard, And A NodeMCU ESP8266.
   - *Wiring*: Connect A Jumper Wire To The Selected VCC Pin Of The NodeMCU. Connect The Jumper Wire To The Anode Pin Of The LED.
      Do The Same For The GND/Cathode Pins But Connect The Resistor In It.
      Your Wiring Is Ready.
   - *Usage*: Blinks The LED In An SOS Pattern.

7. **TemperatureInterfacingWIthESP8266: [TEMPERATUREINTERFACINGWITHESP8266]**
   - *Description*: Interfaces The DHT22 Temperature Sensor With ESP8266.
   - *Components*: DHT22 Temperature Sensor, 3 Jumper Wires, Breadboard, NodeMCU ESP8266.
   - *Wiring*: Connect The 3V3 Pin On The ESP8266 To The DHT22:VCC Pin On The Sensor.
      Connect The Selected Pin (In This Code, The D2 Pin) To The DHT22:SDA Pin On The Sensor.
      Leave Out The DHT22:NC Pin.
      Connect The GND Pin On The ESP8266 To The DHT22:GND Pin On The ESP8266.
   - *Usage*: Measures The Temperature And Humidity Around You.

## Getting Started

### Prerequisites

- Arduino IDE: Install the Arduino IDE from [arduino.cc](https://www.arduino.cc/en/software).
- ESP8266 Board Support: Follow the instructions to add ESP8266 board support in the Arduino IDE.
- Additional Libraries: DHT22 Library, Blynk Library.
### Uploading Code

1. Clone this repository to your local machine.
   ```bash
   git clone https://github.com/Cpd879/ESP8266-Projects.git
