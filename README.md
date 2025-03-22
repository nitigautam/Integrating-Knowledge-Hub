# Integrating-Knowledge-Hub
This project demonstrates a low-cost, portable system for mapping a 2D representation of a room using an ultrasonic sensor connected to an Arduino. The system calculates and visualizes coordinates based on distance measurements and angular positions. The generated map can assist in applications such as robotics navigation, small-scale surveying, and spatial visualization.

Target Beneficiary:-

The primary beneficiaries of this project include:

* Robotics enthusiasts.

* Students and educators in STEM disciplines.

* Developers working on indoor mapping or navigation systems.

The primary objective of this project is to design and implement a portable, low-cost system capable of generating a 2D map of a room using basic sensor measurements. This system will:

* Capture distance data using an HC-SR04 ultrasonic sensor at varying angles.

* Process the data to calculate Cartesian coordinates using trigonometric algorithms.

* Dynamically visualize the results in real-time using Python-based plotting libraries.

* Provide a simple, scalable solution that can be adapted for various use cases, such as robotics navigation, indoor mapping for education, and preliminary spatial analysis.

Methodology

5.1 Data Structures and Algorithms Used

* Data Structures: Lists to store distance and coordinate data.

* Algorithms: Trigonometric calculations for coordinate transformation:

ox=d⋅cos⁡(θ)x = d \cdot \cos(\theta)x=d⋅cos(θ)

oy=d⋅sin⁡(θ)y = d \cdot \sin(\theta)y=d⋅sin(θ)

5.2 Tech Stack

Programming Languages:

* Python (for visualization)
* C++ (Arduino sketch)

Libraries Used:

* matplotlib for real-time plotting.

* pyserial for communication between Arduino and Python.

5.3 System Requirements

* Operating System: Linux-based system (e.g., Linux Mint or Ubuntu 22.04).

* Software: Python 3.x, Arduino IDE.

5.4 Hardware Requirements

* Arduino (Uno).

* HC-SR04 Ultrasonic Sensor.

* Jumper wires, breadboard.

* Laptop for processing and visualization.


![image](https://github.com/user-attachments/assets/c5157fd1-9480-47bb-ab16-12ec52745e6c)

Conclusion

This project successfully demonstrates that room mapping can be achieved with minimal resources, showcasing a system that is both cost-effective and functional. 
By integrating simple hardware like the Arduino and HC-SR04 ultrasonic sensor with Python for visualization, it provides a practical introduction to spatial data processing and mapping.
The results validate the system’s effectiveness in creating a basic 2D map of a room, making it a viable solution for scenarios where expensive mapping tools are impractical. This implementation serves as a foundation for further development, including potential upgrades such as:

1. Servo Motor Integration: Automating sensor rotation to eliminate manual intervention.

2. Enhanced Accuracy: Using multiple sensors or improving algorithms to minimize noise and errors in data.

3. 3D Mapping Capability: Adding vertical measurements to extend the system for 3D space visualization.

4. Wireless Communication: Implementing Bluetooth or Wi-Fi modules for remote control and data transmission.

By addressing the limitations of cost and complexity found in advanced mapping systems, this project offers a meaningful contribution to the field of accessible and affordable indoor mapping solutions. It also encourages further experimentation and innovation among students, hobbyists, and developers.




