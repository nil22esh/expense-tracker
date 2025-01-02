# Expense Tracker Application

## App Demo [Click Here](https://phenomenal-lolly-b59053.netlify.app/)

## Overview

The **Expense Tracker** application is a simple and intuitive tool for tracking your expenses and income. This React-based project allows users to:

- Add new transactions (income or expense).
- Edit existing transactions.
- Delete transactions.
- View a summary of total balance, income, and expenses.

---

## Features

- **Add Transaction**: Record expenses or income with a description and amount.
- **Edit Transaction**: Modify existing transactions.
- **Delete Transaction**: Remove unwanted transactions.
- **Summary Dashboard**:
  - Displays total balance.
  - Shows total income and expenses separately.
- **Interactive UI**: Hover effects and smooth updates for better user experience.

---

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/nil22esh/expense-tracker.git
   ```

2. Navigate to the project directory:

   ```bash
   cd expense-tracker
   ```

3. Install dependencies:

   ```bash
   npm install
   ```

4. Start the development server:

   ```bash
   npm start
   ```

5. Open your browser and navigate to:
   ```
   http://localhost:3000
   ```

---

## Project Structure

```
client/
├── src/
│   ├── components/
│   │   ├── ExpenseForm/
│   │   │   └── ExpenseForm.js
│   │   ├── ExpenseInfo/
│   │   │   └── ExpenseInfo.js
│   │   ├── ExpenseList/
│   │   │   └── ExpenseList.js
│   │   ├── Transaction/
│   │   │   └── Transaction.js
│   ├── App.js
│   ├── App.css
│   └── index.js
├── public/
│   ├── index.html
│   └── images/
├── package.json
└── README.md
```

---

## Components

### 1. **ExpenseForm**

Handles adding and editing transactions. It uses React's `useRef` and `useEffect` for controlled form inputs.

### 2. **ExpenseInfo**

Displays the total balance, income, and expenses. Calculates values dynamically based on the transactions list.

### 3. **ExpenseList**

Lists all transactions and uses the `Transaction` component for individual items.

### 4. **Transaction**

Represents a single transaction with hover effects and options to edit or delete.

### 5. **App**

The main component managing state and logic using `useReducer` and `useState` hooks.

---

## State Management

- **Reducer Function**: Handles adding, updating, and deleting transactions.
- **Global State**: Maintained using the `useReducer` hook.
- **Local State**: Used for handling the currently selected transaction for editing.

---

## Styling

The application is styled using CSS modules for component-level scoping.

- `ExpenseForm.module.css`
- `ExpenseInfo.module.css`
- `ExpenseList.module.css`
- `Transaction.module.css`
- `App.css`

---

## Contributing

Contributions are welcome! Please follow these steps:

---
