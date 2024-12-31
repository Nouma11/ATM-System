# ATM Management System in C++

**An efficient, console-based ATM management application.**

This project is a C++ program that simulates an ATM system. It supports user authentication, quick withdrawals, normal withdrawals, deposits, and balance inquiries. The program uses file-based storage to maintain client information.

## Features

- **User Authentication:**
  - Users login with account numbers and PINs.
  - Secure access to their account information.

- **Quick Withdrawals:**
  - Predefined withdrawal amounts ranging from $20 to $1000.
  - Ensures withdrawal limits are adhered to.

- **Normal Withdrawals:**
  - User-defined withdrawal amounts that are multiples of 5.
  - Prevents overdraws with balance validation.

- **Deposits:**
  - Allows users to deposit amounts into their accounts.

- **Balance Inquiry:**
  - Displays the current balance of the logged-in user.

## File Structure

- `Client.txt`: Stores client account information in a formatted structure.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Nouma11/atm-management-system.git


## Usage

After setting up the program, run the executable to begin interacting with the ATM system. Below is an example of how the interaction works:

### Example Interaction
```plaintext
---------------------------------
            Login Screen
---------------------------------
Enter Account Number? 123456
Enter PinCode? ****
===========================================
            ATM Main Menu Screen
===========================================
[1] Quick Withdraw.
[2] Normal Withdraw.
[3] Deposit.
[4] Check Balance.
[5] LogOut.
===========================================

