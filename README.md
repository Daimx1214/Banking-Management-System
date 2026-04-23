# 🏦 Console Banking Application (C++)

A command-line based banking simulator designed to demonstrate structured programming and object-oriented design principles in C++. This application replicates essential banking workflows in a simplified environment.

## 📖 Project Summary

This program provides a minimal yet functional simulation of a banking system where users can manage a single account through a text-based interface. The goal of the project is to practice designing modular code, handling user input effectively, and maintaining data integrity using encapsulation.

It serves as a foundational project for understanding how real-world systems can be modeled programmatically.
## ✨ Key Functionalities

* Create and initialize a bank account with user details
* Add funds with proper validation to prevent invalid input
* Withdraw money while ensuring sufficient balance
* Display account information including current balance
* Continuous interaction through a loop-driven menu system
* Controlled access to data using private class members

## 🛠️ Tech Stack & Concepts

* **Programming Language:** C++
* **Concepts Applied:**

  * Object-Oriented Programming
  * Encapsulation and Data Protection
  * Function-based modular design
  * Input validation and error handling
* **Tools:** Any standard C++ IDE or compiler

## 🧱 Implementation Details

The application revolves around a class that represents a bank account, storing all necessary information such as account ID, account holder name, and balance as private attributes.

Operations like deposit, withdrawal, and display are implemented as member functions. A loop in the main function ensures that the program remains active until the user decides to terminate it.

## ⚙️ Getting Started

### Requirements

* C++ compiler (e.g., g++)

### Run the Program

```bash id="run_code"
git clone https://github.com/your-username/console-banking-app.git
cd console-banking-app

g++ main.cpp -o app
./app
```
## 🧪 How to Use

After running the program, a menu will appear. Select an option by entering the corresponding number to perform actions such as creating an account, depositing funds, withdrawing money, or viewing account details.

## 🚧 Possible Extensions

* Introduce authentication (PIN or password system)
* Store account data using file handling for persistence
* Support multiple users with dynamic data structures
* Add transaction logs for tracking operations
* Expand into a graphical or web-based interface

## 🎯 Learning Outcomes

* Strengthened understanding of OOP fundamentals in C++
* Gained experience in building interactive console programs
* Learned how to validate and manage user input safely
* Improved ability to structure and organize code logically
* Understood the basics of simulating real-world systems
