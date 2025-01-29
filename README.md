Table of Contents

Introduction
Hardware Requirements
Software Requirements
System Description
Usage
Code Explanation

Introduction
This project implements an electronic voting system using Arduino, allowing users to cast their votes securely and efficiently. The system consists of a keypad for user input, an LCD display for feedback, and LEDs for visual indications.

Hardware Requirements
Arduino Board (e.g., Arduino Uno)
Keypad (4x4 matrix)
LCD Display (16x2)
LEDs (Red, Green, Blue, and White)
Breadboard and Jumper Wires
Software Requirements
Arduino IDE (version 1.8.x or later)
LiquidCrystal_I2C library
Keypad library

System Description
The system has the following features:
User authentication using a unique ID and password
Voting for a specific party using a keypad input
Display of voting results and party-wise vote counts
Option to view the overall election results
Automatic removal of users after voting

Usage
Connect the hardware components as per the circuit diagram.
Upload the code to the Arduino board using the Arduino IDE.
Enter your unique ID using the keypad.
Enter your password using the keypad.
Cast your vote by entering the party number.
View the voting results and party-wise vote counts.

Code Explanation
The code consists of the following sections:
setup(): Initializes the LCD display, keypad, and LEDs.
loop(): Handles user input, authentication, and voting.
authenticateUser(): Verifies the user's ID and password.
removeUser(): Removes the user from the system after voting.

Contributing
Contributions are welcome! To contribute, please fork this repository, make your changes, and submit a pull request.


Example Use Case
To use this system, simply enter your unique ID and password using the keypad. Once authenticated, you can cast your vote by entering the party number. The system will display the voting results and party-wise vote counts.
