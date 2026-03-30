# Bank Managment System in Java
![Java](https://img.shields.io/badge/Language-Java-red.svg) 

## Overview

This project is a basic banking system developed in Java that allows users to perform essential banking operations such as account creation, login, balance checking, fund transfers, and more.

## Features

* Login: Existing users can securely access their accounts using their account number and PIN.
* Account Creation: New users can register and create a bank account.
* Balance Inquiry: Users can check their current account balance.
* Account Details: Users can view their personal and account information.
* Fund Transfer: Users can transfer money between different accounts.
* Transaction History: Users can view and track all past transactions.
* Account Closure: Users can close their account and remove their data from the system.

## Usage

When the program starts, users are presented with two options:

1. Login - For existing users
2. Create Account - For new users

### For Existing Users:

* Enter your account number and PIN (stored in credentials.txt).
* After successful login, a menu will be displayed with all available banking operations.

### For New Users:

* Follow the on-screen instructions to create a new account by entering the required details.

## Project Structure

* Main: Entry point of the application; displays initial options (login or register).
* Login: Handles user authentication and validates user credentials.
* Creation: Manages new account registration.
* BalanceInquiry: Retrieves and displays account balance.
* AccountDetails: Displays detailed user and account information.
* Transaction: Handles fund transfers between accounts.
* Deletion: Manages account closure and removes user data.

## File Structure

* credentials.txt: Stores account numbers and PINs of users.
* userDB.txt: Contains user details such as name, account number, and contact information.
* balanceDB.txt: Maintains account balances for all users.
* acc_[accountNumber].txt: Stores transaction history for each individual account.

## How to Run the Project in IntelliJ IDEA

Follow these steps to run the Bank Management System project using IntelliJ IDEA:

### 1. Install Required Software

* Install Java JDK (8 or above)
* Install IntelliJ IDEA

---

### 2. Clone the Repository

Open terminal or command prompt and run:

git clone https://github.com/sqlxe/Bank-Management-System.git

Or download the ZIP and extract it.

---

### 3. Open Project in IntelliJ

1. Open IntelliJ IDEA
2. Click on Open
3. Select the project folder
4. Wait for IntelliJ to index the project

---

### 4. Configure JDK

1. Go to File → Project Structure → Project
2. Set Project SDK to your installed JDK (e.g., Java 8/11/17)

---

### 5. Locate Main File

* Navigate to:
  src → Main.java
* This file contains the main method (public static void main)

---

### 6. Run the Project

1. Open Main.java
2. Click the green Run button (▶) at the top
   OR
3. Right-click inside the file and click Run 'Main.main()'

---

### 7. Output

* The program will start running in the Run Console
* Follow on-screen instructions (menu options like deposit, withdraw, etc.)

---

### Important Notes

* Make sure all .java files are inside the src folder
* If using a database (MySQL), ensure:

  * Database is running
  * JDBC driver is added
  * Credentials are correctly set in code

---

### Troubleshooting

* Error: No JDK found → Set JDK in Project Structure
* Error: Cannot find symbol → Rebuild project (Build → Rebuild Project)
* Program not running → Ensure you are running the correct Main.java file


## Author

This project was created by [Aditya Telikicharla](https://github.com/sqlxe)

