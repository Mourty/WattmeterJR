# WattmeterJR

This is a smaller cheaper version of the wattmeter described here https://github.com/Mourty/Wattmeter-Project

This version of the measurment board is greatly different than the original and required seperate firmware, but can interface with the service from the original just fine. This version doesn't have the super capacitor and boost converter. It also forgoes the voltage transformer in favor of a voltage divider. All parts that can be surface mount are. This is to save space and cost. The ESP32 used here also isn't a dev module and doesn't have the normal USB interface and requires a seperate UART programming device.


![WattmeterJR Board Render.](<Hardware/Board Render.png>)
