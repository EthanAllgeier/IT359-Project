# IT359-Project
Project for IT 359 \
Here is the link to our video presentation: https://youtu.be/hIphTGCk6Fo

Evil Twin Attack – Fossil Fanatics \
Project Purpose \
This project demonstrates how an Evil Twin Wi-Fi attack works using an ESP32 Marauder and a custom Evil Portal phishing page.
An Evil Twin attack occurs when an attacker creates a fake Wi-Fi network that looks identical to a legitimate one (e.g., “isunet”) to trick users into connecting.
Once connected, the attacker can capture login attempts and observe network traffic.
This project is for educational and ethical cybersecurity training only.

Dependencies & Required Tools \
The following tools and libraries were used:
Hardware \
ESP32 Marauder device
Computer with USB connection
Wi-Fi network for testing
Software \
ESP32 Marauder Firmware
Evil Portal (for hosting fake login pages)
GitHub Evil Portal workflow (to create and upload pages)
Any HTML/CSS editor (for designing fake login page

Setup & Execution Instructions \
1. Flash ESP32 Marauder
Download the ESP32 Marauder firmware
Connect the ESP32 to your computer
Flash the firmware using the provided flashing tool
2. Create and Upload the Evil Portal Page
Use any HTML/CSS editor to design your phishing-style login page.
Save your page as an .html file.
Insert the MicroSD card into your computer.
Upload the .html file to the SD card inside the portal directory (or root, depending on Marauder version).
Insert the SD card back into the Marauder.
3. Configure Evil Portal Settings on Marauder
Power on the ESP32 Marauder.
Navigate to the Evil Portal section in the Marauder interface.
Select your uploaded HTML page from the available portal files.
Save or confirm your choice so Marauder knows which page to serve.
4. Run the Attack Demo
Connect a test device to the cloned SSID
The device will be redirected to your fake login page
Entered credentials appear in the Evil Portal logs
Demonstrate how users can be tricked into giving up sensitive information

Usage Guide + Examples \
Example: Cloning a University Login Page
Team recreated the layout

Example: What a Victim Sees \
When a victim clicks the fake Wi-Fi network:
They see a login page identical to the real one
They may enter credentials without noticing the difference
The attacker receives the submitted data instantly

We followed https://github.com/justcallmekoko/ESP32Marauder/wiki/evil-portal-workflow to help with any issues faced during the project.
