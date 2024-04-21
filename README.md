# EEE3088F
Micro-Mouse Robot Project
Overview

This project involves designing and implementing a micro-mouse robot, focusing on the design of the hardware power and sensing subsystems. The project is divided into four modules: the processor, motherboard, sensing, and power.

Project Structure

Processor: Utilizes an STM32L476 microcontroller for processing tasks.
Motherboard: Connects all PCBs together and serves as the base board for other modules.
Sensing: Responsible for detecting and sensing objects.
Power: Powers the entire system, operates two motors, charges a battery, and provides battery voltage sensing.

Power Subsystem
The power subsystem must meet the following requirements:

- Operate two motors efficiently.
- Charge a battery from a 5V input.
- Provide analog battery voltage sensing for monitoring the state of charge (SoC).
- Include an ON/OFF switch for controlling power to the system.

Sensing Subsystem
The sensing subsystem must meet the following requirements:

- Detect objects in the robot's environment.
- Provide data to the processor for navigation and obstacle avoidance.
- Integrate with the motherboard for communication and data transfer.

How to Use

Assembly: Follow the provided assembly instructions to connect the power and sensing subsystems to the motherboard.
Testing: Use the provided testing procedures to verify that the power and sensing subsystems meet all requirements and specifications.
Integration: Integrate the power and sensing subsystems with the rest of the robot system, ensuring proper functionality and communication between modules.

Contributors

Chloe James(JMSCHL002)

Mitra Ramchuran(RMCMIT001)

License
This project is licensed under the MIT License. See the LICENSE file for details
