# Smart-Watering-System-using-STM32-and-ESP8266

  Nowadays, there is an increasing trend in making devices wireless and user friendly and this project helps to do so by making the user water their plants without having to be physically near the plants to water them.
  
Existing Smart Irrigation systems are built to monitor moisture content and present it on an LCD display panel. However, it just shows the status of the soil and water pump and is wired to the STM32, so the user can't see the information if they aren't close to the system.

Improving on this, we made this an IOT based project by adding a ESP8266 (Esp-01) WIFI Module to create a Web-Server to remotely display the sensor values as well as control the water pump at the click of a button and also added a DHT11 sensor to detect surrounding Temperature and Humidity. The server is also made global using port forwarding with the help of ngrok so the user can control the pump wirelessly and analyse the conditions from anywhere with a device connected to the internet.

This project is designed to switch ON/OFF the water pump using the button on the ESP-01 webserver and to display the sensor values i.e. DHT-11 (Humidity and Temperature) and Moisture on the Web Server. It is also designed to automatically switch the water pump ON/OFF if the moisture value in the soil is less than a defined limit of Moisture (30%). Additionally, if the temperature or the humidity exceeds predetermined safe levels (Temp>30oC or out of the range 30-60%), it will display an alert to warn the user of harmful temperature conditions.

## Hardware Setup
![Hardware](https://user-images.githubusercontent.com/70696174/180646739-7f3a2560-bad3-4d23-9118-ac996ad6e136.JPG)

## Webserver
![Webserver](https://user-images.githubusercontent.com/70696174/180646741-4ccffed8-c4a8-460c-9d80-55ab49a3a6ca.JPG)

Note: Each code can be executed using Arduino ide.
