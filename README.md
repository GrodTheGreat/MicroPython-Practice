# MicroPython Practice
This repo is a place to store some projects as I practice MicroPython

## Projects
### 1. **Hello World! LED Blinking**

**Overview:**
Create a simple program to blink an LED.

**Skills Focus:**
- Basic MicroPython syntax
- Using GPIO (General Purpose Input/Output) pins
- Setting up a development environment

**Technologies/Frameworks:**
- MicroPython on a microcontroller (like ESP8266, ESP32, or PyBoard)
- Basic understanding of circuits

**Tasks:**
- Write a program to turn an LED on and off with a delay.
- Understand how to configure GPIO pins.

### 2. **Button Controlled LED**

**Overview:**
Expand on the LED project by adding a button to control the LED.

**Skills Focus:**
- Reading input from GPIO
- Debouncing buttons
- Event-driven programming

**Technologies/Frameworks:**
- MicroPython libraries for GPIO input

**Tasks:**
- Modify the LED program to turn the LED on or off based on button presses.
- Implement debouncing to ensure the button press is accurately read.

### 3. **Temperature Sensor with Display**

**Overview:**
Read temperature data from a sensor and display it on an LCD or OLED screen.

**Skills Focus:**
- Working with sensors (e.g., DHT11 or DS18B20)
- Interfacing with display modules
- Data formatting and conversion

**Technologies/Frameworks:**
- MicroPython libraries for sensors and displays

**Tasks:**
- Read temperature data from the sensor.
- Display the data on a screen.
- Handle different units (Celsius and Fahrenheit).

### 4. **Data Logging to an SD Card**

**Overview:**
Log sensor data to an SD card for later analysis.

**Skills Focus:**
- File handling in MicroPython
- Working with SD card modules
- Time-stamping data entries

**Technologies/Frameworks:**
- MicroPython filesystem libraries

**Tasks:**
- Write data to an SD card.
- Implement time-stamping using a real-time clock (RTC) module.
- Ensure data integrity on the SD card.

### 5. **WiFi Controlled LED**

**Overview:**
Control an LED via a web interface over WiFi.

**Skills Focus:**
- Networking in MicroPython
- Setting up a basic web server
- Handling HTTP requests

**Technologies/Frameworks:**
- MicroPython network library
- Microcontrollers with WiFi (e.g., ESP8266, ESP32)

**Tasks:**
- Set up a web server.
- Create a web interface to control the LED.
- Handle GET and POST requests.

### 6. **IoT Temperature Monitoring System**

**Overview:**
Monitor temperature remotely and view the data on a web interface.

**Skills Focus:**
- Combining sensors with WiFi
- Data serialization (JSON)
- Real-time data updates

**Technologies/Frameworks:**
- MQTT protocol for IoT
- WebSocket or similar for real-time updates

**Tasks:**
- Read temperature data and send it to a web server.
- Implement an MQTT client to publish/subscribe to temperature data.
- Create a dynamic web page to display real-time data.

### 7. **Home Automation: Controlling Devices via Voice Commands**

**Overview:**
Control devices like lights and fans using voice commands.

**Skills Focus:**
- Integrating with voice assistant APIs (like Google Assistant or Alexa)
- Advanced networking
- Writing complex control logic

**Technologies/Frameworks:**
- MicroPython HTTP library
- External APIs for voice assistants

**Tasks:**
- Set up the microcontroller to receive commands from a voice assistant.
- Write code to control devices based on received commands.
- Implement security measures for the control system.

### 8. **Remote Weather Station**

**Overview:**
Build a complete weather station that reports data to a remote server.

**Skills Focus:**
- Working with multiple sensors (temperature, humidity, pressure)
- Sending data to a cloud service
- Data visualization

**Technologies/Frameworks:**
- MicroPython and cloud services (like AWS, ThingSpeak)
- Visualization tools (like Matplotlib, Bokeh)

**Tasks:**
- Collect data from various sensors.
- Send data to a remote server/cloud service.
- Create a web dashboard to visualize the weather data.

### 9. **Smart Home Dashboard**

**Overview:**
Create a dashboard to control and monitor various home devices.

**Skills Focus:**
- Building complex user interfaces
- Integrating multiple systems
- User authentication

**Technologies/Frameworks:**
- MicroPython with web frameworks
- JavaScript for the frontend

**Tasks:**
- Design a web interface to control and monitor devices.
- Implement user authentication.
- Integrate data from various devices.

### 10. **Robotic Arm Control**

**Overview:**
Build and program a robotic arm to perform simple tasks.

**Skills Focus:**
- Working with motors and servos
- Complex control algorithms
- Real-time processing

**Technologies/Frameworks:**
- MicroPython libraries for motor control
- Robotics principles

**Tasks:**
- Control a robotic arm using MicroPython.
- Implement inverse kinematics for precise control.
- Create a user interface to define tasks for the robotic arm.
