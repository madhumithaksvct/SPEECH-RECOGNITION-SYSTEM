# SPEECH-RECOGNITION-SYSTEM

*COMPANY* : CODETECH IT SOLUTIONS

*NAME* : MADHUMITHA K

*INTERN ID* : CT08LRW

*DOMAIN* : EMBEDDED SYSTEMS

*DURATION* : 4 WEEKS

*MENTORS* : NEELA SANTOSH

*Description* :

This program enables the ESP32 to control four LEDs and a fan remotely using MQTT over Wi-Fi, making it ideal for home automation. The ESP32 subscribes to the MQTT topic "home/commands" to listen for specific commands like "LED1=ON" or "FAN=OFF" to control the connected devices. The ESP32 connects to the Wi-Fi network and the MQTT broker (HiveMQ). Upon receiving a command, it turns the corresponding device (LED or fan) on or off. The program supports various commands for controlling each LED and the fan, providing real-time feedback via the serial monitor. 

To add voice recognition, an external voice module like the Elechouse Voice Recognition Module V3 can be used. This allows the ESP32 to understand voice commands, enabling users to control devices by speaking commands like "LED1 ON" or "Fan OFF." The ESP32 listens for these voice commands through serial communication and executes the corresponding actions, such as toggling LEDs or controlling the fan. Alternatively, cloud-based voice recognition services like Google Assistant or Amazon Alexa can be used to send MQTT messages, allowing voice control through these platforms. This integration enhances the project's functionality by combining both MQTT and voice commands for easy device management.

*OUTPUT:*

![Image](https://github.com/user-attachments/assets/4a36ddd6-c5cc-4e97-8c08-2affbe9dd09c)



