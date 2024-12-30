# Banking Program

## Overview
The **Banking Program** is a simple Python application designed to simulate basic banking operations such as checking account balance, depositing money, and withdrawing money. This project is ideal for learning and demonstrating core Python programming concepts like functions, loops, conditionals, and user input handling.

---

## Features
- **Check Balance**: View your current account balance.
- **Deposit Money**: Add funds to your account.
- **Withdraw Money**: Withdraw funds with built-in safeguards against overdrafts and invalid transactions.
- **Exit Program**: Safely terminate the program.

---

## How It Works
1. The user interacts with a menu-driven interface.
2. Each menu option corresponds to a specific banking operation.
3. The account balance updates dynamically based on deposits or withdrawals.

---

## Prerequisites
- Python 3.x installed on your system.
- A terminal or IDE (e.g., Visual Studio Code, PyCharm) to run the program.

---

## Setup
1. Clone or download this repository to your local machine.
2. Navigate to the program directory.
3. Run the program using the command:
   ```bash
   python banking_program.py

Usage
Launch the program.
Select an option from the menu:
1: Show Balance.
2: Deposit Money.
3: Withdraw Money.
4: Exit Program.
Example Run:
*********************
   Banking Program   
*********************
1.Show Balance
2.Deposit
3.Withdraw
4.Exit
*********************
Enter your choice (1-4): 2
*********************
Enter an amount to be deposited: 100
*********************
Your balance is $100.00
*********************

Code Structure
show_balance(balance): Displays the current account balance.
deposit(): Allows the user to deposit funds and validates the input.
withdraw(balance): Enables fund withdrawal while checking for sufficient balance and valid amounts.
main(): The program's entry point, managing user interaction and menu navigation.

Potential Enhancements
Add a login system to support multiple users.
Include transaction history tracking.
Enable persistent data storage using a database or file system.
Implement interest calculations for savings accounts.

Contributing
Contributions are welcome! Feel free to fork the repository, make enhancements, and submit pull requests.

License
This project is licensed under the MIT License. See the LICENSE file for more information.

MIT License

Copyright (c) 2024 Joseph Mtakai

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
