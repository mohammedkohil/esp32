# esp32
Before starting this installation procedure, make sure you have the latest version of the Arduino IDE installed in your computer.
To install the ESP32 In your Arduino IDE, go to File> Preferences
Enter the following into the “Additional Board Manager URLs” field: https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_index.json
Open the Boards Manager. Go to Tools > Board > Boards Manager
Search for ESP32 and press install button for the “ESP32 by Espressif Systems“:
That’s it. It should be installed after a few seconds.
to Testing the Installation Select your Board in Tools > Board menu (in my case it’s the DOIT ESP32 DEVKIT V1)
Select the Port (if you don’t see the COM Port in your Arduino IDE, you need to install the CP210x USB to UART Bridge VCP Drivers)
Open the following example under File > Examples > WiFi (ESP32) > WiFiScan
A new sketch opens in your Arduino IDE
Press the Upload button in the Arduino IDE. Wait a few seconds while the code compiles and uploads to your board. 
If everything went as expected, you should see a “Done uploading.” message.
Open the Arduino IDE Serial Monitor at a baud rate of 115200:
Press the ESP32 on-board Enable button and you should see the networks available near your ESP32:
