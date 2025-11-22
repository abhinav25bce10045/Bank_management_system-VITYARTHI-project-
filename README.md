Python Console Bank Management System

Project Overview

This project is a complete, console-based Bank Management System built in Python. It simulates core banking functionalities, allowing users to manage accounts, including creation, deposits, withdrawals, viewing details, and deletion. The sysPython Console Bank Management System

Project Overview

This project presents the complete Bank Management System that is implemented in Python. It simulates core banking activities, namely, creating an account, depositing money, withdrawing cash, viewing details, and deleting accounts. It follows a clear and modular architecture, in view of demonstrating effective usage of Python functions and package structure while handling distinct business logics.

Features

The system will perform the following key banking activities:

Create_account: A new user can create an account by supplying all the details required, along with a unique automatically generated account number, and the information is persisted in a file or a simple database.

Deposit Funds (Deposit_amount): This allows the user to deposit funds into an existing account by validating the account number.

Withdraw Funds: Enables Users to withdraw money from an account, providing the logic needed for minimum balance and checking on sufficient funds.

Display Account Details: Display_account retrieves and displays the current balance and account information of a given account number.

Delete Account (Delete_account): Removes an account from the system permanently after confirmation.

Main Menu - main.py: A simple, interactive console to navigate between the major functions.

Technologies and Tools Used

Tool/Technology

Purpose

Python 3.x

The main programming language in which the implementation is done.

Modular Programming

Used to segregate concerns, such as deposit logic and display logic, into separate files/packages.

Console Interface

Standard Input/Output for user interaction.

Simple Data Storage

Implied, e.g., using a JSON file, CSV file, or Python dictionaries for persistence.

Installation and Setup

Requirements

You must have Python 3.x installed on your system.

Steps to Run

Clone the Repository:

git clone https://github.com/your-username/bank-management-system.git


cd bank-management-system

Run the Main Application File:


python main.py

Passover Testing Instructions

Start the application by executing python main.py.

Test 1: Create Account: Enter 1 for Create_account. Enter initial details. Note generated account number.

Test 2: Deposit: Choose option 2 (Deposit_amount). Enter the account number assigned in Test 1 and deposit an amount.

Test 3: Display: Select option 4(Display_account). Enter account number to verify that the amount deposited is reflected in the balance.

Test 4: Withdrawal (Success) Choose option 3 (Withdraw_amount). Withdraw a certain amount below the balance. Check new balance (via option 4).

Test 5: Withdrawal Failure: Select option 3. Try to withdraw more than the balance and note the insufficient funds error message.

Test 6: Delete Account: Select option 5, Delete_account; Enter the account number and confirm deletion. Test 7: Verification: Attempt to view the deleted account option 4, and verify the "Account not found" message.tem is designed with a clear, modular architecture to demonstrate effective use of Python functions and package structure for handling distinct business logic operations.

Features

The system implements the following core banking operations:

Account Creation (Create_account): Allows a new user to open an account by providing necessary details, generating a unique account number, and storing it persistently (e.g., in a file or simple database).

Deposit Funds (Deposit_amount): Enables users to add funds to an existing account after validating the account number.

Withdraw Funds (Withdraw_amount): Allows users to take money out of an account, including logic for checking the minimum balance and sufficient funds.

Display Account Details (Display_account): Fetches and displays the current balance and account information for a specified account number.

Delete Account (Delete_account): Permanently removes an account from the system after confirmation.

Main Menu (main.py): Provides a simple, interactive console interface for navigating between the major functions.

Technologies and Tools Used

Tool/Technology

Purpose

Python 3.x

The primary programming language for implementation.

Modular Programming

Utilized to separate concerns (e.g., deposit logic, display logic) into distinct files/packages.

Console Interface

Standard I/O (Input/Output) for user interaction.

Simple Data Storage

(Implied, e.g., using a JSON file, CSV file, or Python dictionaries for persistence.)

Installation and Setup

Prerequisites

You must have Python 3.x installed on your system.

Steps to Run

Clone the Repository:

git clone [https://github.com/your-username/bank-management-system.git](https://github.com/your-username/bank-management-system.git)
cd bank-management-system


Run the Main Application File:

python main.py


Instructions for Testing

Start the application: Run python main.py.

Test 1: Create Account: Select option 1 (Create_account). Enter initial details. Note the generated account number.

Test 2: Deposit: Select option 2 (Deposit_amount). Enter the account number from Test 1 and deposit an amount.

Test 3: Display: Select option 4 (Display_account). Enter the account number to verify the deposited amount is reflected in the balance.

Test 4: Withdrawal (Success): Select option 3 (Withdraw_amount). Withdraw an amount less than the balance. Verify the new balance (using option 4).

Test 5: Withdrawal (Failure): Select option 3. Attempt to withdraw an amount greater than the current balance and observe the insufficient funds error message.

Test 6: Delete Account: Select option 5 (Delete_account). Enter the account number and confirm deletion.

Test 7: Verification: Try to display the deleted account (option 4) and confirm the "Account not found" message.
