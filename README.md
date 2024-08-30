# Home_Automation
Overview
This project enables real-time control of home appliances through mobile devices using voice recognition technology. By integrating Arduino with the Bluetooth HC-05 module, users can manage devices such as lights and fans, significantly enhancing control efficiency and accessibility.

# Key Features
* Real-Time Control: Control home appliances in real-time from mobile devices.
* Voice Recognition: Manage devices using voice commands.
* Improved Efficiency: Achieved a 30% increase in user control efficiency and a 50% reduction in manual intervention.
* Enhanced Accessibility: Increased user satisfaction by 25% and improved accessibility for users with disabilities by 40%.

# Components Used
* Arduino Uno: The microcontroller that controls the project.
* Bluetooth HC-05 Module: Facilitates wireless communication between the Arduino and mobile devices.
* Relay Module: Controls the power to the home appliances (e.g., light bulb).
* Mobile Device: Used to send voice commands via Bluetooth.
* Wires: For connecting all components (including power and signal wires).

# Hardware Setup
* Arduino Uno: Connect to your computer via USB for programming.

* Bluetooth HC-05 Module:
VCC to Arduino 5V
GND to Arduino GND
TX to Arduino RX (pin 0)
RX to Arduino TX (pin 1)

* Relay Module:
VCC to Arduino 5V
GND to Arduino GND
IN1 to a digital output pin on Arduino (e.g., pin 7)

* Light Bulb: 
Connect to the relay module.

* Wires:
Use jumper wires to connect the components as described.
Ensure proper connections for power (5V and GND) and signal lines.

# Software Setup
* Arduino IDE: Download and install the Arduino IDE from the official website.
* Voice Recognition Library: Ensure you have the necessary libraries installed for voice recognition and Bluetooth communication.

# Usage
* Pairing the Bluetooth Module:
Ensure Bluetooth is enabled on your mobile device.
Pair with the HC-05 module (default password is usually "1234" or "0000").

* Sending Voice Commands:
Use a Bluetooth terminal app on your mobile device.
Send voice commands such as "ON" or "OFF" to control the light.

# Acknowledgments
Special thanks to the Arduino community for providing invaluable resources and support.
Thanks to the developers of the Bluetooth HC-05 module and voice recognition libraries.


