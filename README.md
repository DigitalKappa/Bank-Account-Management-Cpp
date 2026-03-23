# Console-Based Banking Management System

A menu-driven C++ program simulating basic banking operations — built to practice OOP, encapsulation, and input validation.

## Overview

This project simulates a basic bank account system through a command-line interface. Users can open an account, deposit or withdraw funds, and check their balance. It reinforces core OOP concepts like encapsulation and class design in a practical, relatable context.

Simple in scope, but it was a useful exercise in building interactive console applications with proper input handling.

## Features

- Open a new bank account with account number and holder name
- Deposit funds with amount validation
- Withdraw funds with balance and negative-amount checks
- View current account details and balance
- Loop-driven menu for continuous operation until exit
- Private data members demonstrating encapsulation

## Technologies Used

- **Language:** C++
- **Concepts:** Classes, Encapsulation, Member Functions, Input Validation
- **IDE:** Visual Studio / Code::Blocks / Dev-C++

## How It Works

A `Bankaccount` class holds private members — account number, name, and balance. Public methods handle each operation. A menu loop in `main()` runs until the user exits, calling the correct method based on their choice.

## Installation & Setup

**Requirements:** g++ compiler or any C++ IDE
```bash
git clone https://github.com/your-username/bank-account-management-cpp.git
cd bank-account-management-cpp

g++ main.cpp -o bank_system
./bank_system
```

## Usage

Run the program. Choose from the menu (1–5) and follow the prompts to open an account, deposit, withdraw, or view your balance.

## Future Improvements

- Add PIN-based account authentication
- Implement transaction history logging
- Add file-based persistent storage using `fstream`
- Support multiple accounts using an array or linked list

## What I Learned

- How encapsulation protects data inside a class
- Writing input validation to prevent bad user data
- Designing a menu-driven loop structure in C++
- How simple real-world systems translate into class-based code
```
tric XOR-based encryption and decryption with a user-defined key — a beginner-friendly introduction to how data security works at the character level.
