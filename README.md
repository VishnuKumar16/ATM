<h1>ATM by Python</h1>
<p>This Python code simulates a basic ATM interface, allowing a user to perform simple banking operations like checking their balance, withdrawing money, and depositing money. Here's a short explanation of how the code works:
</p>
<h3>1. Card Insertion Simulation:

The code starts by printing a message to insert the card and pauses for 5 seconds (time.sleep(5)).

2. PIN Validation:

The user is prompted to enter their ATM PIN. The code checks if the entered PIN (pin) matches the stored password (which is 1234).
If the PIN is correct, the user can proceed with transactions. If not, an error message is shown.

3. Main Menu Loop:

The code enters a while True loop, repeatedly displaying a menu of options:
Check balance
Withdraw balance
Deposit balance
Exit
The user is prompted to choose an option by entering a number.

4. Options Handling:

Option 1: Displays the current balance.
Option 2: Prompts the user to enter an amount to withdraw. The balance is reduced by this amount.
Option 3: Prompts the user to enter an amount to deposit. The balance is increased by this amount.
Option 4: Exits the loop, ending the program.

5. Error Handling:

The code tries to handle invalid inputs by using a try-except block to ensure the user enters a valid number for the menu choice.

6. Exit:

If the user selects option 4, the loop breaks, and the program ends.</h3>

<p>In summary, this code provides a simple ATM interface that allows users to check their balance, withdraw, and deposit money after entering a correct PIN.</p>
