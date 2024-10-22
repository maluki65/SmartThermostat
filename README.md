# SmartThermostat


## Overview
The Smart Thermostat project demonstrates how to control the temperature of a room using a DHT22 temperature sensor, an OLED/LCD display, a keypad for user input, and a fan. The system allows the user to set a target temperature, and when the room temperature exceeds this target, the fan automatically turns on. The display provides real-time feedback on the current temperature, target temperature, and fan status.

## Components Used:
- DHT22 Temperature Sensor: Measures the room temperature.
- OLED/LCD Display: Displays the current temperature, the target temperature, and fan status (either "ON" or "OFF").
- Keypad: Allows the user to input a target temperature.
- Fan: Automatically turns on when the room temperature exceeds the user-defined target temperature.
- Buzzer: Provides an alert when the temperature reaches a critical level.

## Features:
1. Temperature Monitoring:
   - The DHT22 sensor continuously monitors the current room temperature and updates the display in real time.

2. Target Temperature Setting:
   - The user can set the desired target temperature via the keypad.
   - The thermostat compares the current temperature with the target temperature.

3. Automatic Fan Control:
   - If the current temperature exceeds the target temperature, the fan is turned on automatically.
   - The fan turns off when the room temperature falls below the target.

4. Display Information:
   - The OLED/LCD screen shows:
     - Current temperature
     - Target temperature
     - Fan status (either "ON" or "OFF").

5. Buzzer:
   - An alert buzzer can be added to provide a warning sound when the temperature reaches a critical level (e.g., a very high temperature threshold).

## Key Components:
- DHT22 Sensor: For measuring temperature and humidity.
- Keypad: For user input of target temperature.
- OLED/LCD Display: To visually show temperature information and fan status.
- Fan: Activated when temperature exceeds the set threshold.
