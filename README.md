# Simple Gym Management System
This is a  basic lightweight, console-based Python application designed to help gym owners or administrators manage their member records efficiently.

I built this to practice Object-Oriented Programming (OOP) concepts in Python, specifically focusing on class structures, dictionary management, and user input handling.

# What Can It Do?


This tool handles the basics of gym administration without needing a complex database. 

# Here are the main features:

1.  Add New Members: Inputs details like ID, Name, Age, and Gender.

2.  Smart BMI Calculator: Automatically calculates a member's Body Mass Index (BMI) based on the weight (kg) and height (m) you provide during registration.

3.  Member Lookup: Search for a specific member by their ID to see their contact info and health status (Underweight, Normal, or Overweight).

4.  View Directory: Displays a clean, formatted table of all currently registered members.

5.  Remove Members: Deletes members from the system when they cancel their subscription.

6. choose catogery: to choose which member ship to choose basic, premium, vip.

7.  exit: exit from program

 How It Works (Under the Hood)


#  The project uses two main classes:

 1. Member: Acts as a blueprint for a single person, holding data like ID, name, and calculated BMI.

2. GymManager: The engine of the app. It uses a Python Dictionary ({}) to store members for fast lookups (O(1) time complexity) using the Member ID as the key.

 # How to Run It
You don't need to install any external libraries! This runs on standard Python.

Ensure you have Python installed (version 3.6+ recommended).

Save the code into a file named gym_system.py.

Open your terminal or command prompt.

Run the command:

Bash

python gym_system.py
 Example Usage
Once the program starts, you will see a menu like this:

Plaintext

===
   GYM MANAGEMENT SYSTEM    
====
1. Add Member
2. View All Members
3. Search Member (Details & BMI)
4. Delete Member
5. choose member ship option(basic,premium,vip)
6. Exit
Just type the number of your choice and hit Enter!

   ** Important Note ** 
Data Persistence: Currently, this system uses in-memory storage. This means that if you close the program (Exit), the member list will be reset. It is designed this way for simplicity and demonstration purposes.

 # Future Improvements
If I were to expand this project later, I would add:
File Handling (.csv or .json): To save member data so it doesn't disappear when the program closes.

Input Validation: Stronger checks to ensure phone numbers are valid or IDs aren't left blank.

Subscription Tracking: Adding dates to track when a membership expires.
 
               #  Author: SAMRIDH MISHRA           Language: Python 3 {.py}

