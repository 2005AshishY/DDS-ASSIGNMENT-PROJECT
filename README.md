💰 Personal Finance Tracker – Features

Array of Structures for Storage

Uses an array of Transaction structures to hold details of all income and expenses.

Each transaction stores:

Date (YYYY-MM-DD)

Type (Income / Expense)

Category (e.g., Food, Salary, Rent)

Description

Amount

Add Transaction

Allows user to enter a new income or expense.

Automatically stored in the array.

List All Transactions

Displays a formatted table of all transactions with IDs, dates, type, category, description, and amount.

Sorting Options

Sort transactions by:

Date (oldest → newest)

Amount (highest → lowest)

Type (income first)

Category (alphabetical)

Description (alphabetical)

Search Feature

Search transactions by a keyword in the description (case-insensitive).

Filter Transactions

Show only expenses over a specified amount (e.g., expenses > $100).

Totals & Savings

Calculate and display:

Total Income

Total Expense

Net Savings (Income – Expense)

File Save/Load (Persistence)

Save all transactions into a file (data.tsv).

Load transactions from file later (replace or append).

Ensures data is not lost between program runs.

Monthly ASCII Bar Chart (Bonus Feature)

Shows an ASCII bar chart of monthly spending (expenses only).

Example:

Aug | ########################  1200.00
Sep | #########               450.00


Menu-Driven System

Simple interface to navigate all features:

1) Add transaction
2) List transactions
3) Sort
4) Search (description)
5) Filter: expenses over amount
6) Show totals
7) Save to file
8) Load from file
9) Monthly spending chart
0) Exit
