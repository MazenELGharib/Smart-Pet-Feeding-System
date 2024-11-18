# Smart Pet Feeding System  

The **Smart Pet Feeding System** is an IoT project designed to automate pet feeding and provide real-time monitoring of food levels in the feeding container. The system uses sensors to measure the weight of the food container and communicates with a HiveMQ broker via MQTT over WebSocket (WSS) for seamless data transmission. The user interface (UI) is built using **React.js**, offering users an intuitive way to monitor the container's status and remotely control the feeding process.  

---

## Features  

- **Real-Time Monitoring**: Tracks the weight of the food container and updates the status in real-time.  
- **MQTT Communication**: Utilizes **HiveMQ** for data transmission via MQTT over WebSocket (WSS).  
- **Remote Control**: Allows users to automate or manually control the feeding process.  
- **User-Friendly Interface**: A responsive UI built with **React.js** for ease of use.  

---

## Technologies Used  

- **ESP8266**: Collects sensor data and publishes it to HiveMQ.  
- **React.js**: Provides a dynamic and responsive web interface for monitoring and control.  
- **MQTT Protocol**: Ensures efficient and reliable communication between the ESP8266 and the UI.  
- **HiveMQ**: Acts as the MQTT broker for real-time data exchange.  
- **Weight Sensors**: Measures the food container's weight to determine its status.  

---

## How It Works  

1. **Data Collection**: The ESP8266 collects weight data from the sensors attached to the feeding container.  
2. **Data Transmission**: The ESP8266 publishes the sensor readings to a HiveMQ broker using MQTT.  
3. **Real-Time Updates**: The React.js UI subscribes to the HiveMQ broker and displays the container's status in real-time.  
4. **Remote Control**: Users can use the UI to control the feeding mechanism remotely.  
