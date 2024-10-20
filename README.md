The code simulates a simple ATM interface and bank account management system.

💼 *Bank_Account Class:*
1. It represents a bank account with a private balance attribute.
2. The constructor initializes the initial balance.
3. Methods allow for checking balance, depositing money, and withdrawing money.
4. It ensures that deposits and withdrawals are valid and updates the balance accordingly.

🏧 *ATM_Machine Class:*
1. It interacts with the user by displaying a menu of ATM options.
2. It runs in a loop until the user chooses to exit.
3. Based on the user's choice, it either checks the balance, deposits money, withdraws money, or exits the ATM.

🔄 *ATM_Interface Class (Main):*
1. It creates a Bank_Account object with an initial balance of ₹1000.
2. It creates an ATM_Machine object using the Bank_Account object.
3. It runs the ATM interface.

Overall, this code allows users to interact with a simulated ATM machine to perform banking operations such as checking balance, depositing money, and withdrawing money.
