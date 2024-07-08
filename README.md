# Bank Management System

## Overview

The Bank Management System is a simple C-based application that allows users to manage bank accounts. It supports functionalities such as creating a new account, viewing account details, modifying account information, and deleting accounts. The program reads and writes account information to a file named `record.dat`.

## Features

- **Create New Account**: Allows users to create a new bank account by entering personal and account details.
- **View Account Details**: Displays a list of all accounts with details such as account number, name, address, and phone number.
- **Modify Account**: Enables users to modify existing account details.
- **Delete Account**: Permits the deletion of an account from the system.
- **Main Menu Navigation**: Provides an easy way to navigate between the main menu and other functionalities.
- **Exit Option**: Allows users to exit the application.

## Prerequisites

- C Compiler (GCC recommended)

## Getting Started

### Installation

1. **Clone the Repository**:
    ```sh
    git clone https://github.com/yourusername/bank-management-system.git
    ```
2. **Navigate to the Project Directory**:
    ```sh
    cd bank-management-system
    ```

### Compilation

Compile the program using GCC or any other C compiler:

```sh
gcc bank_management_system.c -o bank_management_system
```

### Running the Program

After compiling, you can run the program with the following command:

```sh
./bank_management_system
```

## Program Structure

### Functions

- **main()**: Entry point of the program. Displays the login screen and navigates to the main menu.
- **menu()**: Displays the main menu with options to create, view, modify, delete accounts, or exit the program.
- **create_account()**: Prompts the user for account details and saves them to `record.dat`.
- **view_list()**: Reads and displays all accounts from `record.dat`.
- **modify()**: Allows the user to modify existing account details.
- **delete()**: Deletes an account based on the account number provided by the user.
- **close()**: Exits the program.
- **password()**: Authenticates the user before accessing the main menu.

### File Handling

- **record.dat**: The file where all account information is stored. The program reads from and writes to this file to manage account data.

## Usage

1. **Login**: On running the program, you will be prompted to enter a password. Enter the password to access the main menu.
2. **Main Menu**: From the main menu, choose the desired operation by entering the corresponding number.
    - **1**: Create a new account.
    - **2**: View list of all accounts.
    - **3**: Modify an existing account.
    - **4**: Delete an account.
    - **0**: Exit the program.
3. **Create Account**: Follow the prompts to enter account details such as name, date of birth, address, citizenship, phone number, account type, and initial deposit.
4. **View Accounts**: View the list of all accounts stored in `record.dat`.
5. **Modify Account**: Enter the account number of the account to be modified and update the required details.
6. **Delete Account**: Enter the account number of the account to be deleted.

## Error Handling

- The program includes basic error handling for invalid inputs and file operations.
- It also ensures that the user cannot navigate to other functions without entering the correct password.

## Contribution

Feel free to contribute to this project by forking the repository and creating pull requests. You can also open issues for any bugs or feature requests.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Inspired by simple C programming examples for file handling and console applications.

---

**Note**: Customize the repository URL and other placeholders as per your GitHub repository details.
