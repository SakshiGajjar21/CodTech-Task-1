Name: Sakshi Gajjar
Company: CODTECH IT SOLUTION
ID: CT08DS1603
Domain: IoT (Internet of things)
Duration: June to July 2024
Mentor: Muzzamil Ahemed

PROJECT OVERVIEW

![image](https://github.com/SakshiGajjar21/CodTech-Task-1/assets/174607973/be1972b6-7d30-474d-b05a-b1f98b8ba332)
Using the Wokwi Arduino simulator, I built a comprehensive weather monitoring project. It includes sensor readings for temperature, humidity, and pressure, computes rainfall using a predefined formula, and presents the data dynamically on a simulated LCD display. This setup allows for interactive testing and visualization of weather conditions in a virtual environment.

COMPONENTS:

DHT22 Sensor: This sensor is pivotal for accurate temperature and humidity measurements, providing crucial data for weather analysis.
Analog Pressure Sensor: Used to capture atmospheric pressure readings, contributing to the calculation of estimated rainfall.
LCD Display (16x2): Integrated via I2C communication for real-time visualization of temperature, humidity, pressure, and computed rainfall data.
Arduino Uno Microcontroller: Central to the project, it processes sensor inputs, performs calculations for rainfall estimation, and controls the display output.
Wokwi Arduino Simulator: This online tool facilitates virtual development and testing, replicating the Arduino environment for simulation and debugging purposes

PROECT DESCRIPTION:

The weather monitoring project uses an Arduino Uno with sensors and an LCD display to monitor environmental conditions. Upon startup, the Arduino initializes the LCD display and reads data from a DHT22 sensor for temperature and humidity, as well as an analog pressure sensor for atmospheric pressure. These inputs are crucial for real-time weather analysis.

In its main loop, the Arduino continuously reads and processes sensor data. It displays current temperature (in Celsius), humidity (as a percentage), and atmospheric pressure (in hPa) on the LCD. It also calculates estimated rainfall based on a formula incorporating temperature, humidity, and pressure readings. The LCD updates periodically to show these values, providing users with instant weather updates.

Using the Wokwi Arduino simulator, this entire process is simulated virtually. The simulator replicates Arduino hardware and sensors, allowing developers to test and refine the weather monitoring system's functionality and accuracy without physical components. This virtual environment supports iterative development and ensures reliability before real-world deployment.
