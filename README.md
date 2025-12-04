# IT359-Project
Project for IT 359

The README.md File: This is the homepage for your project. It must contain:
The link to your video presentation at the very top.
A clear description of the project's purpose.
A list of all dependencies and libraries required.
Step-by-step instructions for setup and execution.
A usage guide with examples.


Evil Twin Attack – Fossil Fanatics
Project Purpose
This project demonstrates how an Evil Twin Wi-Fi attack works using an ESP32 Marauder and a custom Evil Portal phishing page.
An Evil Twin attack occurs when an attacker creates a fake Wi-Fi network that looks identical to a legitimate one (e.g., “isunet”) to trick users into connecting.
Once connected, the attacker can capture login attempts and observe network traffic.
This project is for educational and ethical cybersecurity training only.

Dependencies & Required Tools
The following tools and libraries were used:
Hardware
ESP32 Marauder device
Computer with USB connection
Wi-Fi network for testing
Software
ESP32 Marauder Firmware
Evil Portal (for hosting fake login pages)
GitHub Evil Portal workflow (to create and upload pages)
Any HTML/CSS editor (for designing fake login page

Setup & Execution Instructions
1. Flash ESP32 Marauder
Download the ESP32 Marauder firmware
Connect the ESP32 to your computer
Flash the firmware using the provided flashing tool
2. Load the Evil Portal
Open the Evil Portal workflow on GitHub
Upload or paste your phishing login page HTML/CSS
Deploy the portal to the ESP32 device
3. Create the Evil Twin Network
Power on the ESP32
Access the Marauder interface
Scan for nearby Wi-Fi networks
Select the target SSID (example: isunet)
Choose “Clone / Evil Twin”
Start broadcasting the fake access point
4. Run the Attack Demo
Connect a test device to the cloned SSID
The device will be redirected to your fake login page
Entered credentials appear in the Evil Portal logs
Demonstrate how users can be tricked into giving up sensitive information

Usage Guide + Examples
Example: Cloning a University Login Page
Team recreated the layout

Example: What a Victim Sees
When a victim clicks the fake Wi-Fi network:
They see a login page identical to the real one
They may enter credentials without noticing the difference
The attacker receives the submitted data instantly
