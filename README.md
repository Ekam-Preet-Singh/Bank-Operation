# Bank-Operation

## Bank Account Demonstration

This code provides a demonstration of a basic banking system implemented using object-oriented programming in Python. It includes the following classes:

- `BankAccount`: Represents a basic bank account and provides methods to get and set the account number and name.
- `FixedDeposit`: Inherits from `BankAccount` and represents a fixed deposit account. It adds attributes for duration, amount, and rate of interest.
- `RecurringDeposit`: Inherits from `BankAccount` and represents a recurring deposit account. It adds attributes for duration, monthly payment, and rate of interest.
- `BankDemo`: Demonstrates the functionality of the banking system by providing a menu-driven interface.

### Features

- Read and write fixed deposit accounts: Users can enter details such as account number, name, duration, amount, and rate of interest. The program creates a `FixedDeposit` object and displays the entered details.
- Read and write recurring deposit accounts: Users can enter details such as account number, name, duration, monthly payment, and rate of interest. The program creates a `RecurringDeposit` object and displays the entered details.
- User-friendly interface: The program presents a menu for selecting the desired operation and guides the user through entering the required details.
- Exit option: Users can choose to exit the program at any time.

### Usage

1. Clone the repository to your local machine.

2. Open a terminal or command prompt.

3. Navigate to the directory where the repository is cloned.

4. Run the following command to execute the script:

```bash:
python Bank Management System.py
```

5. The program will display a menu with options to select.

6. Choose the desired option by entering the corresponding number and pressing Enter.

7. Follow the on-screen prompts to enter the required details for fixed deposit or recurring deposit accounts.

8. Once the details are entered, the program will display the entered information.

9. To continue using the program, you can choose another option from the menu.

10. If you wish to exit the program, select the "3. Exit" option from the menu.

### Demo

Here's a demo of how to input the contents to run the file:

1. Select your choice: 1 (for Fixed Deposit)

2. Enter Account Number: 123456

3. Enter Account Name: John Doe

4. Enter Duration (in months): 12

5. Enter Amount: 10000

6. Enter Rate of Interest: 5.0

    Output:

    ```bash:
    Fixed Deposit Details are...
    Account Number: 123456
    Account Name: John Doe
    Duration: 12 months
    Amount: $10000
    Rate of Interest: 5.0%
    ```

7. To continue, choose another option from the menu.

8. To exit the program, select the "3. Exit" option.
