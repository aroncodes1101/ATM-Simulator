# ATM Simulator Using Python
Overview of the Project
This project is a simple command-line ATM Simulator built using Python.
It replicates basic banking operations such as user login, checking balance, cash withdrawal, cash lodgement, and PIN change.
The simulator is designed to be secure, user-friendly, and reliable, making it ideal for understanding how banking systems function at a basic level.
________________________________________
## Features
1. User Authentication
•	Secure login with username and 4-digit PIN
•	PIN entered using getpass for hidden input
•	Account lock after 3 invalid attempts
2. Account Operations
•	Balance Inquiry: View current balance
•	Cash Withdrawal: Withdraw funds with balance validation
•	Cash Lodgement: Deposit money with valid denominations
•	PIN Change: Update PIN securely
3. Error Handling
•	Invalid username
•	Wrong PIN attempts
•	Insufficient funds
•	Invalid input formats
4. Session Control
•	Smooth exit from the system with proper termination messages
________________________________________
## Technologies / Tools Used
•	Programming Language: Python
•	Key Modules:
o	getpass – For secure PIN input
•	Data Storage:
o	In-memory lists storing users, PINs, and account balances
________________________________________
## Steps to Install & Run the Project
Prerequisites
Ensure you have:
•	Python 3.x installed
•	A terminal/command prompt available
Installation & Running
1.	Download or clone the project folder
2.	Open the terminal inside the project directory
3.	Run the Python script using:
python atm_simulator.py
4.	Follow the on-screen instructions to log in and perform transactions
________________________________________
## Instructions for Testing
1. Positive Testing
•	Use valid username & PIN
•	Perform successful withdrawals
•	Test correct deposits and balance view
2. Negative Testing
•	Enter an invalid username
•	Test 3 incorrect PIN attempts to trigger account lock
•	Attempt withdrawals larger than current balance
•	Try depositing or withdrawing invalid amounts
3. Edge Case Testing
•	Withdraw/Deposit zero
•	Change PIN to the same existing PIN
•	Enter non-numeric values

# Sample Output:
•	Login & Menu
![image alt](https://github.com/aroncodes1101/ATM-Simulator/blob/fdc80dce8e71c85a4a7e810d815072f0aed4f055/Login%20and%20Menu%20Page.png)
•	Transaction
Withdraw:
![image alt](

Lodge:
![image alt](https://github.com/aroncodes1101/ATM-Simulator/blob/77507098ac00868c36a1c3d791b3a2115031b456/lodge.png)

USER NAME: USER1
PIN: 1111
Author: ARON SMITH THOMAS
