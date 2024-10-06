# Personal Finance Tracker

## Overview

The **Personal Finance Tracker** is a Python-based tool for tracking personal finances. It allows users to log incomes and expenses, categorize them, and visualize their financial data over time. This project uses a command-line interface and data visualization libraries to provide users with detailed financial insights.

## Features

- **Income Tracking**: Log income entries with details such as date, category, amount, and notes.
- **Expense Tracking**: Record expenses with similar details.
- **Visualization**: Display bar charts, pie charts, and line plots to show financial trends and distributions.
- **Category-based Summary**: Break down income and expenses by category for better analysis.

## Requirements

To run this project, make sure you have the following dependencies installed:

- Python 3.8 or higher

- Required libraries:

  ```
  bash
  
  
  Copy code
  pip install pandas matplotlib datetime
  ```

## How to Run

1. Clone the repository to your local machine:

   ```
   bash
   
   
   Copy code
   git clone https://github.com/yourusername/personal-finance-tracker.git
   ```

2. Navigate to the project directory:

   ```
   bash
   
   
   Copy code
   cd personal-finance-tracker
   ```

3. Open the Jupyter Notebook or run the script directly using the command line:

   ```
   bash
   
   
   Copy code
   python personal_finance_tracker.py
   ```

4. Follow the on-screen instructions to log incomes, record expenses, and view summary statistics.

## Usage

1. **Start the Program**: When you run the script, you'll be prompted with a menu to choose from:
   - Enter Incomes
   - Enter Expenses
   - Show statistics
   - Exit
2. **Enter Incomes**: When prompted, enter the income details such as date, category, amount, and optional notes.
3. **Enter Expenses**: Similarly, enter expense details with date, category, amount, and notes.
4. **Show Statistics**: The tool will display:
   - A summary of total income, total expenses, and remaining balance.
   - Bar charts comparing income and expense amounts over time.
   - Pie charts showing the distribution of categories for both income and expenses.
   - Line plot showing the trend of income versus expenses over time.
5. **Exit**: Type `0` to exit the program.

## Project Structure

```
bashCopy codepersonal-finance-tracker/
│
├── personal_finance_tracker.py       # Main Python script file
├── README.md                         # Project documentation
└── requirements.txt                  # List of required packages
```

## Functionality

### Functions

- `income()`: Prompts the user to enter income details and returns a list of income dictionaries.
- `expense()`: Prompts the user to enter expense details and returns a list of expense dictionaries.
- `summaryy(income_list, expense_list)`: Generates visualizations and statistics based on the logged incomes and expenses.

### Main Program

- The `main()` function acts as the entry point, providing a menu-driven interface for users to interact with the finance tracker.

## Contact

For any questions or suggestions, feel free to reach out at mohamedawad.b.2001@gmail.com