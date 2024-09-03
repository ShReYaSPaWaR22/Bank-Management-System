# Bank Management System

A straightforward desktop application for managing banking records. Records are saved directly in a binary file (`account.dat`) to streamline data handling and improve efficiency.

## Features

- **Create New Account**: Set up a new account with account number, holder name, account type (Saving or Current), and initial deposit.
- **Modify Account**: Update account holder's name, account type, or balance.
- **Balance Enquiry**: Check the balance of a specific account.
- **Deposit & Withdraw**: Add or subtract money from an account.
- **Account Holder List**: View a list of all accounts and their details.
- **Close Account**: Delete an account from the system.
- **Exit**: Close the application.

## Launch

Run the `bms.exe` file directly to start the application.

For testing purposes, both passwords are set to `"password"`.

- **Admin**: Full access to manipulate data.
- **User**: Limited to viewing data.

## Usage

1. **Create New Account**: Choose option 1 from the menu to create a new account. Follow the prompts to enter the account details.
2. **Modify Account**: Choose option 2 to modify an existing account. Enter the account number and update the desired details.
3. **Balance Enquiry**: Choose option 3 to check the balance of an account by entering the account number.
4. **Deposit/Withdraw**: Choose options 4 or 5 to deposit into or withdraw from an account, respectively.
5. **View All Accounts**: Choose option 6 to list all accounts and their details.
6. **Close Account**: Choose option 7 to close an account by entering the account number.
7. **Exit**: Choose option 8 to exit the application.

## Installation and Running

1. Install a C++ compiler (e.g., GCC).
2. Write your C++ code and save it with the `.cpp` extension.
3. Open the terminal (Linux/Mac) or Command Prompt (Windows).
4. Navigate to the directory containing your C++ source code.
5. Compile the code using the command:
   ```bash
   g++ -o bms bms.cpp
6. Run the executable using:
   ```bash
   ./bms (Linux/Mac)
   bms.exe (Windows)
