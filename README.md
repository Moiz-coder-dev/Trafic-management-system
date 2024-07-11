# Trafic-management-system


Traffic Control System
This repository contains a C++ console application that implements a traffic control system with AI capabilities for vehicle registration, data storage, and various vehicle-related operations.

Overview
The application is designed to manage traffic control by focusing on vehicle registration, data handling, and AI-based vehicle scanning. The key functionalities include displaying, updating, searching, and deleting vehicle records.

Key Classes and Functions
Class history
This class handles the basic functionalities of vehicle data management.

Attributes:

username: Stores the username for accessing the system.
password: Stores the password for accessing the system.
Methods:

History(): Prompts the user for credentials and provides options for managing vehicle records.
show(): Displays all stored vehicle data.
update(): Updates the information of a vehicle based on its registration number.
search(): Searches for a vehicle's data using its registration number.
del(): Deletes either all records or a specific record based on the registration number.
Class AI (Inherits from history)
This class adds AI capabilities for vehicle scanning and handling.

Methods:
wellcomeAI(): Introduces the AI model and provides options to start scanning vehicles or view history.
car1(): Simulates scanning a vehicle and generates random data for vehicle attributes.
myai(int y): Assigns and displays the tax and speed data for a scanned vehicle, and prompts the user for further actions.
Class wellcome (Inherits from AI and user)
This class integrates the functionalities from the history and AI classes, providing a welcome interface for the application.

Constructor:

Loads data and displays a welcome message.
Methods:

car(): Placeholder for additional functionalities related to vehicle handling.
How to Use
Clone the Repository:

sh
Copy code

Compile the Code:

sh
Copy code
g++ -o traffic_control main.cpp
Run the Application:

sh
Copy code
./traffic_control
Features
User Authentication: Secure login system using a username and password.
Vehicle Data Management: Add, update, search, and delete vehicle records.
AI-Based Vehicle Scanning: Simulate scanning of vehicles and assign attributes like tax and speed.
Historical Data Handling: View and manage historical vehicle data.
Dependencies
Standard C++ libraries (iostream, ctime, string, fstream)
Windows-specific libraries (windows.h, conio.h)
License
This project is licensed under the MIT License. See the LICENSE file for more details.
