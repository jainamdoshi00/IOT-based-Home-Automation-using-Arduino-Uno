# IoT-Based Home Automation System using Arduino Uno

This project is functional **home automation system** using Arduino Uno, integrating sensors and actuators to monitor and control home environment parameters such as **motion**, **temperature** and **light intensity**.

## Features

- **Motion Detection**: Uses a PIR sensor to detect human presence and trigger a buzzer.
- **Temperature Control**: Monitors room temperature using an analog temperature sensor and automatically adjusts fan speed using PWM.
- **Smart Lighting**: Turns on an LED automatically when ambient light is low using an LDR sensor.
- **LCD Display**: Displays real-time temperature data on a 16x2 LCD screen.

## Technologies Used

- Arduino Uno
- C/C++ (Arduino IDE)
- PIR Sensor
- LDR Sensor
- Analog Temperature Sensor (LM35 or similar)
- Fan (DC Motor)
- Buzzer
- 16x2 LCD Display
- Breadboard & Jumper Wires


## How It Works

1. **Motion Detection**: When the PIR sensor detects motion, it triggers a buzzer alert.
2. **Temperature-Based Fan Control**:
   - Below 30°C: Fan is off.
   - Above 30°C: Fan speed increases proportionally with temperature.
3. **Automatic Lighting**:
   - If ambient light is below a certain threshold, the LED lights up.
4. **Live Temperature Display**:
   - Temperature is displayed continuously on the LCD.
