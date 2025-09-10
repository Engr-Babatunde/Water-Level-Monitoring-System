💧 **Water Level Monitoring System**

📌 **Project Overview**

This project is a microcontroller-based water level monitoring system that uses an ultrasonic sensor to track water depth and indicate calibrated levels at 25%, 50%, 75%, and 100%. Each level is represented by an LED indicator, making it simple to visualize the water status in real time.

The system was implemented using an Arduino microcontroller, making it flexible, reliable, and easy to modify for household or industrial use.

⚙️ **Features**

📊 Ultrasonic Sensor Measurement: Accurately measures water level without direct contact.

🟢 LED Indicators: Four LEDs correspond to 25%, 50%, 75%, and 100% tank capacity.

🔔 Optional Alert: Buzzer can trigger when water reaches full level.

🔧 Microcontroller-based: Easy to expand with displays or IoT modules.

🛠️ **Components Used**

Arduino (UNO)

HC-SR04 Ultrasonic Sensor

4 LEDs (Green, Yellow, Orange, Red)

Resistors

Buzzer (optional)

Jumper wires & breadboard

Power supply

🖥️ **How It Works**

The ultrasonic sensor measures the distance between the water surface and the sensor.

The Arduino calculates the water level percentage.

Based on thresholds, the corresponding LEDs light up:

25% → LED 1

50% → LED 2

75% → LED 3

100% → LED 4 (+ buzzer if enabled)

This gives a visual real-time indication of water level.
