# Banking Program

A simple command-line Banking Program written in Python. The project is designed as a beginner-friendly course project and demonstrates functions, loops, conditional statements, user input, return values, and basic validation.

## Project Overview

The program starts with a balance of `$0.00` and provides a four-option menu:

1. Show Balance
2. Deposit
3. Withdraw
4. Exit

The user can deposit money, withdraw money when sufficient funds are available, check the current balance, and exit the program.

## Features

- Display current balance
- Deposit money
- Withdraw money
- Check for insufficient funds
- Reject negative transaction amounts
- Repeat the menu until the user exits
- Handle invalid menu choices

## Technologies Used

- Python 3
- Command-line / Terminal
- Standard Python input and output

No external Python packages are required.

## Project Structure

```text
Banking Program/
├── main.py
├── README.md
├── statement.md
└── docs/
    ├── report.pdf
    └── diagrams/
```

## Requirements

- Python 3.x installed on the system
- A terminal or command prompt

## How to Run

1. Open the project folder in VS Code or another editor.
2. Open a terminal in the project folder.
3. Run:

```bash
python main.py
```

On some systems, use:

```bash
python3 main.py
```

## How to Use

After starting the program, enter one of the following choices:

```text
1. Show Balance
2. Deposit
3. Withdraw
4. Exit
```

### Show Balance

Enter `1` to display the current balance.

### Deposit

Enter `2` and provide the amount to deposit. A negative amount is rejected.

### Withdraw

Enter `3` and provide the amount to withdraw. The program checks the available balance and rejects a withdrawal that is larger than the current balance.

### Exit

Enter `4` to stop the program.

## Example

```text
Banking Program
1.Show Balance
2.Deposit
3.Withdraw
4.Exit
Enter your choice (1-4): 2
Enter an amount to be deposited: 500

Enter your choice (1-4): 1
Your balance is $500.00

Enter your choice (1-4): 3
Enter amount to be withdrawn: 200

Enter your choice (1-4): 1
Your balance is $300.00
```

## Validation Used

The current implementation checks:

- Negative deposit amounts
- Negative withdrawal amounts
- Withdrawal amounts greater than the current balance
- Menu choices outside `1-4`

## Testing

Recommended test cases:

- Start with a zero balance.
- Deposit a positive amount and check the balance.
- Withdraw an amount smaller than the balance.
- Try to withdraw more than the balance.
- Try a negative deposit or withdrawal.
- Enter an invalid menu option.
- Select Exit.

## Current Limitations

This is a small educational banking program. It does not currently provide customer accounts, authentication, persistent storage, transaction history, account-to-account transfers, or a graphical interface.

## Future Enhancements

Possible next versions can add:

- Safer numeric input handling with `try/except`
- Customer accounts and PIN authentication
- Database storage
- Transaction history
- Fund transfers
- Admin/reporting functions
- GUI or web interface

## Author

Student Course Project
