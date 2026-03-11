# ECSE 223: Cheese Wheel Sorting Manager 🧀

A Java-based application for managing and sorting cheese wheels, developed as the capstone project for McGill University's ECSE 223 (Model-Based Programming) course. 

## Project Architecture
This project was built strictly using model-driven engineering principles:
* **UML & Umple:** The entire system architecture was first designed using Umple state machines and UML class diagrams.
* **State Machines:** Robot sorting logic and delivery sequences are governed by strict state-machine rules to prevent edge-case failures.
* **Java Swing/JavaFX:** The frontend interface allowing users to track inventory and manage sorting routines.

<img src="https://github.com/user-attachments/assets/3b3a63b8-756a-429c-ab91-f358ecb6c5c4" alt="UML Diagram" width="100%">

## How to Run the Application

You can run the compiled application directly on your machine without needing to build the source code.

### Prerequisites
* Ensure you have [Java Runtime Environment (JRE)](https://www.java.com/en/download/) installed (Java 11 or higher recommended).

### Installation & Execution
1. **Download the executable:**
   [Download CheeseManager.jar (v1.0.0)](https://github.com/AlyGaber0/ECSE223-CheECSE-Manager/releases/download/v1.0.0/ca.mcgill.ecse.cheecsemanager.jar)

2. **Run via Terminal/Command Prompt:**
   Open your terminal, navigate to the folder where you downloaded the file, and run:
   ```bash
   java -jar CheeseManager.jar
