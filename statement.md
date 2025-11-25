"" Gym Management System (Python)  ""


This project is a CLI-based Gym Management System that I built to practice Object-Oriented Programming (OOP) in Python. The application runs directly in the VS Code integrated terminal and uses a GymManager class to handle operations like registering members and tracking their Body Mass Index (BMI). Currently, the system utilizes a Python dictionary for fast data lookups, meaning all data is stored in temporary memory (RAM) and will reset once the program is closed—this was a conscious design choice to keep the initial version lightweight without external database dependencies.

                        Key Features & How to Run in VS Code:

1. Member Management: Allows adding new members with unique IDs, names, and contact info, as well as viewing a formatted list of all active members.

2. BMI Logic: Automatically calculates BMI based on the height and weight input during registration and categorizes the result (e.g., Normal, Overweight).

3. Search & Delete: Includes functionality to search for specific members by ID to view their status or delete them from the records.