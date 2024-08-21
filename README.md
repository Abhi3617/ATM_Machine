ATM Machine Simulation in Java
An ATM (Automated Teller Machine) simulation in Java is a console-based application that mimics the functionalities of a real ATM machine. The primary purpose of this application is to provide users with the ability to perform basic banking operations such as checking account balance, withdrawing money, depositing money, and exiting the system.
Key Components:

User Interface (UI):
The application usually starts with a welcome message and prompts the user to enter their credentials, typically a PIN or account number.
After successful authentication, the user is presented with a menu of options (e.g., Check Balance, Withdraw, Deposit, Exit).

Account Management:
A class is created to represent a bank account, containing attributes such as accountNumber, pin, balance, and methods for operations like checkBalance(), withdraw(), deposit(), etc.
The balance is updated based on the transactions performed.

Authentication:
The application includes a simple authentication system where the user’s inputted PIN is compared against stored credentials to grant access to their account.

Transaction Processing:
Check Balance: Displays the current balance of the user's account.
Withdraw Money: Allows the user to withdraw a specific amount from their account. The system checks if sufficient funds are available before processing the transaction.
Deposit Money: Permits the user to deposit money into their account, updating the balance accordingly.
Exit: Ends the session and exits the application.

Error Handling:
The application handles errors such as insufficient balance during withdrawal, invalid input, and incorrect PIN.
