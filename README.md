# alexa-with-arduino-and-aws-lambda

#DAY1: Connecting Blynk android app with ESP8266 NodeMCU
Step1: On Arduino IDE, go to Tools> Boards> Board Manager and install ESP8266 if not already installed.
Step2: Upload file ESP8266_blynk on this repository to Node MCU via the port you have connected through.
Step3: Do not forget to generate blynk Auth Key on the android/ ios app and replace the same in the code.
Step4: Create a button for the device in the app and set the output to D4 (default one).

By now, you should be able to connect to your NodeMCU device and switch off/on the default blue light. You can connect to D4 for external usage. Stay tuned to get updates on Alexa based Smart home development.
