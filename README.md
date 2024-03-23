
# Automated Guide Vehicle Prototype - 1

The Automated Guide Vehicle project is a amazing Project that integrates the ESP32 WiFi kit and web application control to create an autonomous guiding system. This system simplifies vehicle navigation by allowing precise control over mechanum wheels, facilitating 360-degree movement and accurate maneuvering through predefined routes or tasks. The project's primary goal is to offer a seamless and efficient solution for automated vehicle navigation in various environments, making it ideal for applications like warehouse logistics, industrial automation, and smart transportation systems.

What sets this project apart is its user-friendly interface and versatility through web app control. With intuitive tools for remote vehicle guidance, users can effortlessly navigate and perform tasks without manual intervention, significantly reducing operational effort. Moreover, the project's second prototype will be integrating advanced features like Lidar for autonomous navigation and proximity sensors for collision detection, enhancing safety and reliability during vehicle operations.

Through its efficient workflow, precise navigation capabilities, and innovative sensor integration, the Automated Guide Vehicle project showcases the practical applications of ESP32 and web app control in autonomous vehicle guidance. It serves as a valuable asset for industries and researchers looking to optimize automation systems, improve safety, and streamline vehicle operations in diverse settings.


## Final Test Prototype

https://github.com/Shreerang01/Automated-Guided-Vehicle/assets/113919844/f0fce209-f473-43ce-90d2-54661988a332


## Circuit Diagram

![WiFi Car](https://github.com/Shreerang01/Automated-Guided-Vehicle/assets/113919844/70250cf7-9a00-4d01-adb1-fadacfd40626)


## Table of Contents

- Installation
- Hardware Requirements 
- Features
- Getting Started
- Usage
- Contributing
- Acknowledgements
- License
## Installation

```bash
  -Go to my project link below
  -Copy/fork it on your account
  -Run Locally by uploading the base code using Arduino IDE
```
    
## Hardware Requirements 

This table outlines the necessary components and quantities required for building an Automated Guided Vehicle (AGV) system. Each component plays a crucial role in the functionality and operation of the AGV, ensuring reliable performance and seamless integration within industrial environments.

Note - Requirements for Prototype 1

| Component                    | Quantity | Description                                   |
|------------------------------|----------|-----------------------------------------------|
| ESP32 WiFi Board             | 1        | Microcontroller board for WiFi connectivity   |
| High Torque 12V DC Motors    | 4        | Motors with high torque for propulsion        |
| Mecanum Wheels               | 4        | Omnidirectional wheels for agile movement     |
| L298N Motor Driver           | 2        | Motor driver module for controlling motors    |
| Aluminum Chassis for AGV     | 1        | Sturdy chassis designed for Automated Guided Vehicles (AGV) |
| Motor-Chassis Connector      | 4        | Connectors for attaching motors to the chassis |
| Battery DC 12V (LiPo 3S)     | 1        | Rechargeable 12V battery for power supply     |
| Battery Connector            | 1        | Connector for connecting the battery to the system |
| Switch                       | 1        | On/off switch for system control               |
| Jumper Wires                 | -        | Wires for electrical connections              |
| Breadboard                   | 1        | Board for prototyping and connecting components|

## Features

- **Integrative Control System:** The Automated Guide Vehicle project seamlessly integrates an ESP32 WiFi kit controlled by a web application, providing a centralized and intuitive control system for precise vehicle navigation and operations.

- **360-Degree Maneuverability:** Equipped with mechanum wheels, the vehicle demonstrates exceptional maneuverability, allowing smooth and precise movement in any direction, enabling it to navigate through complex environments effortlessly.

- **Payload Capacity:** Capable of lifting payloads ranging from 10 to 20 kilograms, the vehicle's robust design ensures efficient transportation of goods or equipment, making it suitable for various industrial and logistical applications.

- **Long Battery Life:** With a two-hour battery life, the vehicle can operate continuously for extended periods, ensuring uninterrupted workflow and minimizing downtime during operations.

- **Enhanced Safety Features:** The second prototype of the vehicle incorporates advanced features such as Lidar for autonomous navigation and proximity sensors for collision detection, enhancing safety and reliability during autonomous operations.
## Getting Started

For Actual Implementation

    1. Clone this repository to your local machine.

    2. Build the Hardware using the Flow Diagram

    3. Open the `wificar.ino` file with all its coordinating files using the Arduino IDE.

    4. Upload the code to your Arduino IDE.

    5. Make sure all the files are in same place.

    6. Run the main file.

    7. Note the Obeservations

## Usage

- **Industrial Logistics:** Industries can implement the Automated Guide Vehicle for automated material handling, transporting goods within warehouses, factories, and distribution centers, optimizing logistics operations and reducing manual labor.

- **Smart Warehousing:** Warehousing facilities can utilize the vehicle for inventory management, order picking, and replenishment tasks, improving inventory accuracy, order fulfillment efficiency, and overall warehouse productivity.

- **Autonomous Transportation:** Transportation sectors can deploy the vehicle for autonomous transportation of goods within controlled environments such as airports, hospitals, and large-scale facilities, ensuring reliable and efficient transportation services.

- **Smart Agriculture:** In agriculture, the vehicle can assist with tasks like crop monitoring, pesticide spraying, and harvesting, contributing to precision farming practices, resource optimization, and increased agricultural productivity.

- **Educational Demonstrations:** Educational institutions and research centers can use the Automated Guide Vehicle as a teaching tool for robotics, automation, and mechatronics courses, providing hands-on experience with autonomous vehicle technologies.

- **Event Management:** Event organizers can employ the vehicle for event logistics, such as transporting equipment, setting up booths, and managing crowd flow, enhancing event coordination and operational efficiency.
## Contributing

Contributions are always welcome!

Please adhere to this project's `code of conduct`.

Anyone can contribute to the project by simply forking the project to your local machine and adding new features and functionalities and and making it more useful.

## Acknowledgements

 - [ESP-32](https://docs.espressif.com/projects/esp-idf/en/stable/esp32/index.html)

- [Mecnum Wheels](https://ai.thestempedia.com/docs/quarky-mecanum-documentation/#:~:text=The%20Quarky%20Mecanum%20Wheel%20Robot,can%20spin%20in%20either%20direction.)

- [AGV's](https://en.wikipedia.org/wiki/Automated_guided_vehicle)

- [Lidar](https://coast.noaa.gov/data/digitalcoast/pdf/lidar-101.pdf)



## License

[MIT](https://choosealicense.com/licenses/mit/)

