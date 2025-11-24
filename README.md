💰 Monthly Budget Planner CLI
A lightweight, command-line interface (CLI) tool written in Python that helps you track your monthly income and expenses. It uses a JSON file for persistent storage, ensuring your financial data is saved between sessions.

✨ Features
Persistent Storage: Automatically saves and loads data using a local monthly_budget_data.json file.

Income Management: Set and update your total monthly income.

Expense Tracking: Add expenses with categories (e.g., Food, Rent) and descriptions.

Financial Summary: View a dashboard showing:

Total Income vs. Total Expenses.

Remaining Balance (or Overdraft warning 🚨).

Percentage breakdown of expenses by category.

Error Handling: Validates numerical inputs to prevent crashes.

🛠️ Prerequisites
To run this script, you need:

Python 3.x installed on your system.

You can check your Python version by running:

Bash

python --version
🚀 Getting Started
Save the Code: Copy the provided Python code and save it into a file named budget_planner.py.

Run the Script: Open your terminal or command prompt, navigate to the folder where you saved the file, and run:

Bash

python budget_planner.py
First Run: On the very first run, the script will create a monthly_budget_data.json file automatically and ask you to set your initial income.

📖 Usage Guide
Once the script is running, use the numeric menu to navigate:

Set/Update Monthly Income: Enter your total budget for the month.

Add New Expense: Input the category, description, and cost of an item.

View Summary: Displays your financial health, including a breakdown of where your money is going.

Exit and Save: Saves any final changes and closes the program.

Example Summary Output
Plaintext

----------------------------------------
          💰 MONTHLY BUDGET SUMMARY 💰
----------------------------------------
Total Monthly Income:    $  5,000.00
Total Expenses Tracked:  $  1,250.00
----------------------------------------
💰 Remaining Budget:     $  3,750.00
----------------------------------------

--- Detailed Expense Breakdown ---
- Rent                : $1,000.00 (20.0%)
- Groceries           : $  250.00 (5.0%)
📂 Project Structure
Plaintext

/project-folder
│
├── budget_planner.py         # The main Python script
└── monthly_budget_data.json  # Auto-generated data file (do not edit manually)
🛡️ Data Management
Your data is stored in monthly_budget_data.json in the same directory as the script.

Backup: You can copy this file to back up your data.

Reset: To start completely fresh, simply delete the monthly_budget_data.json file. The script will create a new one next time it runs
