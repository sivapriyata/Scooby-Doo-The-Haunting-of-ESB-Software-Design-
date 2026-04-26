# Scooby-Doo-The-Haunting-of-ESB-Software-Design-

---

# Scooby Doo: The Haunting of ESB

[cite_start]An interactive, text-based mystery game developed in **Java**[cite: 31]. [cite_start]Players join "The Gang" to solve a paranormal case involving missing computers at the Engineering Science Building (ESB)[cite: 12]. [cite_start]The project showcases advanced **Object-Oriented Programming (OOP)** principles, **Design Patterns**, and **Mobile Sensor Integration**[cite: 174, 626, 641].

##  Game Overview
[cite_start]The Dean of Engineering has hired Scooby-Doo and his friends to investigate electronic gadget thefts from the campus labs[cite: 12, 32].

### Key Gameplay Features:
* [cite_start]**Exploration:** Navigate multiple floors of the ESB, including classrooms, laboratories, and bathrooms[cite: 17, 18].
* [cite_start]**Clue Gathering:** Collect 10 essential clues by interacting with NPCs and using environmental search functions[cite: 19, 21].
* [cite_start]**Sensor-Based Interaction:** Use real-world phone movements (accelerometer, gyro) to perform in-game actions like picking up items or using a flashlight[cite: 20, 169, 172].
* [cite_start]**The Final Showdown:** Once all clues are gathered, unlock the Secret Lair to confront and defeat the villains in a turn-based battle[cite: 22, 78, 545].

##  Technical Architecture

### Design Patterns Used
To ensure a modular and scalable codebase, the following patterns were implemented:
* [cite_start]**Observer/Singleton:** Used for character management and progress tracking[cite: 155, 178].
* [cite_start]**Strategy Pattern:** Defined interaction behaviors for different character types (e.g., `YesInteraction` vs. `NoInteraction`) [cite: 392, 394-411].
* [cite_start]**Template Method:** Standardized the structure of different game scenes (ESB, Classrooms, Bathrooms) while allowing specific logic for each[cite: 251, 336, 361].
* [cite_start]**State Pattern:** Managed the progression and access levels within the ESB building[cite: 412, 413].
* [cite_start]**Command Pattern:** Centralized the player's action inputs within the main game loop[cite: 497, 498].

### Hardware & Multithreading
[cite_start]The game utilizes **Multithreading** to handle real-time sensor data from a mobile device via a TCP connection [cite: 519, 624-626]:
* [cite_start]**Accelerometer:** Used for the "pickup" function to acquire clues[cite: 172, 173].
* [cite_start]**Gyroscope:** Detects rotation to simulate turning on a flashlight in dark areas[cite: 168, 169].
* [cite_start]**Magnetometer:** Acts as a compass for directional movement[cite: 170, 171].

##  Credits

### Development Team
* [cite_start]**Mohammad Ali** (b00088658) [cite: 3]
* [cite_start]**Farhaan Basheer** (b0089008) [cite: 4]
* [cite_start]**Kareem Ahmed** (b00088375) [cite: 5]
* [cite_start]**Sivapriya T Ajith** (g00093499) [cite: 6]

### Academic Oversight
* [cite_start]**Course:** COE 312 - Software Design [cite: 1]
* **Institution:** American University of Sharjah

---
[cite_start]*For a full demonstration of the gameplay, watch the video here: [Project Demo](https://youtu.be/gB3H_5lSVfc?si=ERtpycmbQ_pfkerK)* [cite: 27]
