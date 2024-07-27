# Banking-Application-

The provided Java code is a simple banking application that allows a user to perform basic banking operations such as checking their balance, depositing money, withdrawing money, and checking the previous transaction. The code is structured into two classes: `BankingApplication` and `BankAccount`. Here's a theoretical explanation of the code's functionality:

1. `BankingApplication` Class:
   - This is the main class that contains the `main` method, which is the entry point of the application.
   - It creates an instance of the `BankAccount` class with the customer name "SL DevCode" and customer ID "SL00001".
   - It then calls the `showMenu` method on the `BankAccount` instance to start the application.

2. `BankAccount` Class:
   - This class represents a bank account with attributes such as `balance`, `previousTransaction`, `customerName`, and `customerId`.
   - The constructor initializes the `customerName` and `customerId` with the values passed when creating an instance of the class.
   - The `deposit` method is used to add an amount to the balance and record the transaction.
   - The `withdraw` method is used to subtract an amount from the balance and record the transaction.
   - The `getPreviousTransaction` method prints the details of the last transaction (deposit or withdrawal).
   - The `showMenu` method displays a menu to the user and handles their input to perform the corresponding actions. It uses a `do-while` loop to keep the menu open until the user chooses to exit (option 'E').

The application works as follows:
- The user is presented with a menu of options (A, B, C, D, E) representing different banking operations.
- The user selects an option by entering the corresponding letter.
- The application responds to the user's selection by performing the requested operation or displaying the balance, previous transaction, or an error message for invalid input.
- The application continues to prompt the user for options until the user chooses to exit the system.

The application uses a `Scanner` object to read user input from the console and conditional statements (`switch-case`) to handle the different menu options. The `System.out.println` method is used to display messages and account information to the user.

The application does not include any data persistence, error handling for invalid amounts (such as withdrawing more than the balance), or advanced features like login authentication. It is a simple demonstration of object-oriented programming principles and console-based user interaction in Java.
