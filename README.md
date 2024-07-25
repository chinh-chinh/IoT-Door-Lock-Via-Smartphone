# IoT door lock via smartphone
Utilize an ESP8266 NodeMCU CP2102 and a MC38 magnetic door sensor to create a smart door lock system. Data is sent over Wi-Fi to the Blynk IoT cloud. Users can control and monitor the door's status (open/closed) via the Blynk mobile app or web interface.
## Approach
* **Hardware selection**: We have chosen the necessary hardware components, including NodeMCU, 12VDC electromagnetic lock, single-channel relay module 3.3/5V, MC38 sensor, and a 12V battery for power supply.
*  **Circuit design:** The hardware components are connected according to a predefined circuit design. The NodeMCU is programmed to control the relay module and communicate with the MC38 sensor.
## Scope
* The main purpose of the project is to monitor home security and is intended for experimental and demonstration purposes, with many limitations that prevent practical or commercial application.
* The IoT door lock system is designed to control access/monitor and remotely lock/unlock the door through a phone or other mobile device connected to the Internet.
* It provides remote access and monitoring through the Blynk mobile application.
* The system can be integrated into a broader IoT ecosystem to enhance functionality.
## Limitations
* Due to various external factors such as external force, door design elements, etc., the system may incorrectly detect the door as closed (the door and lock may be misaligned with the lock position).
* The security of the project must be robust because unauthorized access to the IoT system can impact physical security.
* An Internet connection is required for remote access, which can be a limitation in areas with poor connectivity.
* The current design of the project is tailored to a single-door configuration and may require modifications to set up multiple doors.
* Like any IoT system, privacy and data security are important considerations, and users should be cautious about the potential for remote access.
## Key Features
* **Remote Control**: Users can open and close the door using a mobile app or web interface.
* **Real-Time Monitoring**: Check the door's status (open/closed) in real-time via the Blynk app.
* **Wi-Fi Connectivity**: Utilizes home Wi-Fi to connect the door lock system to the internet.
* **Cloud Integration**: Sends data to the Blynk IoT cloud for processing and interaction.
## Technologies and Components
* **Microcontroller**: ESP8266 NodeMCU CP2102
* **Sensor**: MC38 Magnetic Door Sensor
* **Platform**: Blynk IoT Cloud
* **Connectivity**: Wi-Fi
