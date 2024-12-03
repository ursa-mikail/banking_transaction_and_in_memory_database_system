# Banking-Transaction-and-In-Memory-Database-System
This repository demonstrates a comprehensive system with an in-memory database and a banking transaction management system. It supports key database operations, banking account management, transaction handling, and data analytics for financial systems.

## Features
### In-Memory Database Operations
The in-memory database offers operations for managing key-value pairs, similar to how a NoSQL database would operate.

- SET_OR_INCREMENT: Set or increment the value of a field under a specified key.
- GET: Retrieve the current value associated with a specific key.
- DELETE: Remove a specific field from a key.
- NUM_EQUAL_TO: Count how many fields hold a certain value across the database.
- TOP_N_KEYS: Retrieve the top N keys sorted by their modification count.

### Banking Transaction System
A full-fledged banking system that enables transactions like deposits, withdrawals, transfers, and supports account management.

- Transaction Types:

	- Deposit: Adds funds to an account.
	- Withdraw: Withdraws funds from an account.
	- Transfer: Transfers funds between two different accounts.

- Account:

Each account is identified by a unique ID, has a balance, and tracks its transaction history.

- Bank:
	- Manages multiple accounts and facilitates transactions (deposit, withdraw, transfer).

- BankAnalytics:
	- Analyzes banking transactions, identifying accounts with the most transfers, and generating reports on outgoing transactions.

- Merge Functionality:
	- Integrates changes from one account into another (can be used for scenarios like merging accounts with the same owner).

### Operations
	- In-Memory Database Operations
	- Banking Transactions including the merge feature
	- Account Analytics
		- Check Top Accounts by Outgoing Transactions: View the accounts with the highest outgoing transaction amounts.
