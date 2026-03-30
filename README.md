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

## Author

This project was created by [Aditya Telikicharla](https://github.com/sqlxe)

