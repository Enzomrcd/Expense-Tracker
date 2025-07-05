# 💸 Personal Expense Tracker (Desktop App)

A clean, fully offline expense tracker built with **Python**, **customtkinter**, and **SQLite**. Track your daily spending, manage budgets, analyze where your money goes, and export your data — all from a simple desktop app that puts **privacy and usability first**.

---

## 🧩 Features

🖥 **Modern GUI** with `customtkinter`
🧾 Add, view, and delete daily expenses
📊 Visual charts (pie, bar) of spending by category
💰 Set monthly budgets and track overages
🔁 Manage recurring expenses (e.g., rent, subscriptions)
📤 Export data to **CSV** or **Excel (.xlsx)**
💻 Optional command-line interface for power users
🔒 **Fully local** – your data stays on your device

---

## 🗂 Project Structure
    expense_tracker/
    ├── main.py # GUI app entry point
    ├── cli.py # CLI entry point
    ├── config.py # Config settings
    │
    ├── data/
    │ └── expenses.db # Local SQLite database
    │
    ├── models/ # Database models
    ├── services/ # Business logic (tracking, exporting, summaries)
    ├── ui/ # customtkinter-based GUI
    ├── utils/ # Charts, helpers, date functions
    │
    ├── requirements.txt # Dependencies
    └── README.md #You are currently here
---

### 1 Getting Started

### Prerequisites

- Python 3.8 or higher
- pip (Python package manager)

### Installation

    git clone https://github.com/yourusername/expense-tracker.git
    cd expense-tracker

    pip install -r requirements.txt

### GUI USAGE
    python main.py

### CLI USAGE
    Add an expense
    python cli.py add --amount 50 --category Food --note "Lunch"

# View monthly summary
    python cli.py summary

# Export data
    python cli.py export --format excel

### 🔒 Privacy & Offline-First
    This app is 100% offline.

    No internet connection is required

    No data is ever sent to external servers

    All data is stored locally in data/expenses.db

### 🛠️ Roadmap
    Recurring expense automation

    Income tracking

    Category breakdown over time

    Sorting/filtering UI improvements

    Export with custom date ranges

    Dark mode

### 👨‍💻 Contributing
Pull requests are welcome!
If you'd like to suggest features or report bugs, please open an issue.

📄 License
MIT License. See LICENSE for full details.

🙋‍♂️ Author
@enzomrcd