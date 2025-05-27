# 💼 WealthTrack – Personal Finance Manager

WealthTrack is a simple finance management app built using **Flask**, **SQLite**, and **HTML/CSS/JS**. It allows users to:

- Add, view, edit, and delete income and expenses
- Set monthly and category-specific budgets
- Track budget usage
- Submit feedback and contact support
- Use a simple dashboard UI for all modules

---

## 🧰 Requirements

To run this project, the following software is required:

### ✅ Install These First:

1. **Python 3.10+** (Recommended: 3.11 or 3.13)
2. **VS Code** (or any Python IDE)
3. **SQLite Viewer Extension** (for VS Code) – to view `.db` file:
   - Go to Extensions → Search: `SQLite Viewer` → Install

---

## 📦 Install Required Python Packages

Open a terminal and run:

```bash
pip install flask


📁 Folder Structure

WealthTrack/
│
├── db/
│   └── wealthtrack.db         # SQLite database file
│
├── Static/
│   └── global.css             # Styling for all pages
│
├── templates/
│   ├── add_expense.html
│   ├── add_income.html
│   ├── edit_transaction.html
│   ├── delete_transaction.html
│   ├── filter_transactions.html
│   ├── view_transactions.html
│   ├── set_monthly_budget.html
│   ├── set_category_budget.html
│   ├── edit_budget.html
│   ├── delete_budget.html
│   ├── view_budget_summary.html
│   ├── submit_feedback.html
│   ├── contact_support.html
│   ├── request_callback.html
│   ├── rate_usability.html
│   ├── homepage_wealthtrack.html
│   └── feedback_dashboard.html
│
├── app.py                    # Main Flask app
└── README.md                 # You are reading this

🚀 How to Run the App
Follow these steps:

Open VS Code in the WealthTrack/ folder.

In terminal, run the Flask app:

  python app.py

Open your browser and go to:

 http://127.0.0.1:5000/
 That’s your homepage.


