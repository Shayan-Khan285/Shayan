# 🎯 Project Statement: Monthly Budget Tracker

## 1. Project Vision
The vision for the Monthly Budget Tracker is to provide a **simple, reliable, and accessible tool** for individuals to gain better control and visibility over their personal monthly finances. The tool should operate seamlessly from the command line, offering essential tracking capabilities without the complexity of larger financial software.

---

## 2. Project Objectives

The primary objectives of this command-line application are:

* **Financial Clarity:** To enable users to quickly and accurately calculate their remaining budget balance after accounting for all expenditures.
* **Expense Categorization:** To automatically group spending by category, allowing users to identify where the majority of their income is allocated.
* **Data Persistence:** To ensure that all recorded income and expense data is saved and reloaded across sessions, providing continuous financial history.
* **Robustness:** To handle common user errors (like non-numeric input) gracefully, ensuring the application remains stable.

---

## 3. Scope of the Application

### In Scope (Must-Haves)

* **Core CRUD (Create, Read, Update) Operations:**
    * Set and update a single **Total Monthly Income** value.
    * **Add** new expense records (Category, Description, Amount).
* **Reporting:**
    * Display a **Summary** showing Total Income, Total Expenses, and Remaining Balance.
    * Display a **Detailed Breakdown** of spending aggregated by Category, including the percentage of income spent.
* **Data Management:**
    * Use the local file system (`monthly_budget_data.json`) for persistence using the **JSON format**.
    * Handle loading the file when it is missing or corrupted.

### Out of Scope (Future Enhancements)

The current scope does **not** include the following features, which are reserved for potential future versions:

* **Editing/Deleting:** Functionality to modify or remove existing expense entries.
* **Time-based Reporting:** Tracking expenses by date to generate weekly, quarterly, or annual reports.
* **Budget Limits:** Setting predefined spending caps for specific categories.
* **User Interface:** A graphical user interface (GUI); the application remains strictly a Command-Line Interface (CLI) tool.

---

## 4. Key Metrics for Success

The project will be deemed successful if it achieves the following:

* **Accuracy:** The Remaining Balance calculation (Income - Total Expenses) is consistently correct.
* **Persistence:** Data is saved and reloaded correctly 100% of the time.
* **Usability:** A user can successfully record income and expenses and view a summary within a few simple steps via the CLI menu.
