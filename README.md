# Scooby-Doo-The-Haunting-of-ESB-Software-Design-

---

# Scooby Doo: The Haunting of ESB

An interactive, text-based mystery game developed in **Java**. Players join "The Gang" to solve a paranormal case involving missing computers at the Engineering Science Building (ESB). The project showcases advanced **Object-Oriented Programming (OOP)** principles, **Design Patterns**, and **Mobile Sensor Integration**

##  Game Overview
The Dean of Engineering has hired Scooby-Doo and his friends to investigate electronic gadget thefts from the campus labs.

### Key Gameplay Features:
* **Exploration:** Navigate multiple floors of the ESB, including classrooms, laboratories, and bathrooms.
* **Clue Gathering:** Collect 10 essential clues by interacting with NPCs and using environmental search functions.
* **Sensor-Based Interaction:** Use real-world phone movements (accelerometer, gyro) to perform in-game actions like picking up items or using a flashlight.
* **The Final Showdown:** Once all clues are gathered, unlock the Secret Lair to confront and defeat the villains in a turn-based battle.

##  Technical Architecture

### Design Patterns Used
To ensure a modular and scalable codebase, the following patterns were implemented:
* **Observer/Singleton:** Used for character management and progress tracking.
* **Strategy Pattern:** Defined interaction behaviors for different character types (e.g., `YesInteraction` vs. `NoInteraction`) .
* **Template Method:** Standardized the structure of different game scenes (ESB, Classrooms, Bathrooms) while allowing specific logic for each.
* **State Pattern:** Managed the progression and access levels within the ESB building.
* **Command Pattern:** Centralized the player's action inputs within the main game loop.

### Hardware & Multithreading
The game utilizes **Multithreading** to handle real-time sensor data from a mobile device via a TCP connection:
* **Accelerometer:** Used for the "pickup" function to acquire clues.
* **Gyroscope:** Detects rotation to simulate turning on a flashlight in dark areas.
* **Magnetometer:** Acts as a compass for directional movement.

##  Credits

### Development Team
* **Mohammad Ali** (b00088658) 
* **Farhaan Basheer** (b0089008) 
* **Kareem Ahmed** (b00088375) 
* **Sivapriya T Ajith** (g00093499) 

### Academic Oversight
* **Course:** COE 312 - Software Design 
* **Institution:** American University of Sharjah

---
*For a full demonstration of the gameplay, watch the video here: [Project Demo](https://youtu.be/gB3H_5lSVfc?si=ERtpycmbQ_pfkerK)* 
