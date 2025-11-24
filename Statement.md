# ATM Simulator – Statement of the Project
Problem Statement
Modern banking systems require secure, reliable, and user-friendly platforms to allow customers to perform basic financial operations without human assistance.
The aim of this project is to simulate a simple ATM system using Python, where users can log in securely and perform essential banking transactions such as checking balance, withdrawing cash, depositing funds, and updating their PIN.
The system must handle errors gracefully, provide meaningful feedback, and maintain a smooth flow similar to a real ATM experience.
________________________________________
# Scope of the Project
The scope of this project includes the following:
•	Development of a command-line ATM application in Python
•	Implementation of user authentication using username and PIN
•	Managing basic banking transactions (withdrawal, lodgement, balance inquiry)
•	Ensuring non-functional aspects such as security, usability, and reliability
•	Handling invalid inputs, insufficient funds, and multiple failed login attempts
•	Providing a functional simulation suitable for learning and academic demonstration
## Note:
This project uses in-memory lists instead of a real database, making it suitable for educational and basic-level system demonstration but not for production use.
________________________________________
# Target Users
The ATM Simulator is intended for:
•	Students learning Python programming or system simulation
•	Beginners who want to understand how ATM logic and workflows are implemented
•	Educators teaching basic software engineering concepts
•	Developers looking for a simple example of user authentication and transaction handling
________________________________________
# High-Level Features
🔹 1. Secure User Authentication
•	Username and PIN validation
•	Hidden PIN input using getpass
•	Account lock after 3 failed attempts
🔹 2. Account Balance Inquiry
•	View the current account balance in real-time
🔹 3. Cash Withdrawal
•	Withdraw funds
•	Validates sufficient balance
•	Rejects invalid or negative amounts
🔹 4. Cash Lodgement (Deposit)
•	Deposit money
•	Validates denominations and input values
🔹 5. PIN Change
•	Provides a secure method to update the user's PIN
•	Ensures PIN confirmation and format validation
🔹 6. User-Friendly Transaction Flow
•	Clear prompts and instructions
•	Error messages for invalid inputs
•	Smooth navigation through ATM menu options

## Author- Aron Smith Thomas
