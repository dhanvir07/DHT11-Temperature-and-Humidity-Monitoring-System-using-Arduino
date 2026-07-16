The DHT11 Temperature and Humidity Monitoring System using Arduino is a beginner-friendly embedded systems project designed to measure environmental temperature and humidity in real time. The project uses a DHT11 sensor connected to an Arduino Uno to collect sensor data and display the readings on the Arduino IDE Serial Monitor.

The DHT11 sensor continuously measures the surrounding temperature (in degrees Celsius) and relative humidity (in percentage). The Arduino reads the sensor values every two seconds using the DHT Sensor Library and prints the results to the Serial Monitor. If the sensor fails to provide valid data, the program detects the error and displays an appropriate message, improving the reliability of the system.

This project demonstrates the fundamentals of sensor interfacing, serial communication, and real-time data acquisition with Arduino. It is an excellent starting point for beginners and can be extended by adding an LCD or OLED display, data logging, Wi-Fi connectivity (ESP32/ESP8266), or cloud-based monitoring for Internet of Things (IoT) applications.

Key Features
Real-time temperature measurement (°C)
Real-time humidity measurement (%RH)
Automatic sensor error detection
Simple and beginner-friendly Arduino implementation
Easily expandable for IoT and smart environmental monitoring project
