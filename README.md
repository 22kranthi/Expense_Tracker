# 💸 Money Manager - Expense Tracker

A simple and intuitive expense tracking application built with React, Vite, and Tailwind CSS. Track your expenses, categorize them, and manage your budget efficiently with a clean and responsive interface.

## ✨ Features

- **Add Expenses**: Record expenses with title, category, and amount
- **Edit & Delete**: Right-click on any expense to edit or delete it via context menu
- **Category Filtering**: Filter expenses by category for better organization
- **Sorting**: Sort expenses by amount in ascending or descending order
- **Local Storage**: All data is automatically saved in browser's local storage
- **Real-time Total**: Automatically calculates and displays total expenses
- **Responsive Design**: Works seamlessly on desktop and mobile devices
- **Form Validation**: Ensures all required fields are filled before submission

## 🚀 Tech Stack

- **React 18.2.0** - UI library
- **Vite 5.1.3** - Build tool and dev server
- **Tailwind CSS 3.4.1** - Utility-first CSS framework
- **UUID** - Generate unique IDs for expenses
- **LocalStorage** - Client-side data persistence

## 📦 Installation

1. Clone the repository:
```bash
git clone https://github.com/22kranthi/Expense_Tracker.git
cd Expense_Tracker
```

2. Install dependencies:
```bash
yarn install
```

3. Start the development server:
```bash
yarn dev
```

4. Open your browser and navigate to `http://localhost:5173`

## 🛠️ Available Scripts

- `yarn dev` - Start the development server
- `yarn build` - Build for production
- `yarn preview` - Preview production build locally

## 📁 Project Structure

```
Expense_Tracker/
├── src/
│   ├── components/
│   │   ├── AddForm.jsx          # Form component for adding/editing expenses
│   │   ├── ExpenseTable.jsx     # Table displaying all expenses
│   │   ├── ContextMenu.jsx      # Right-click menu for edit/delete
│   │   ├── Header.jsx           # Application header
│   │   ├── Home.jsx             # Main container component
│   │   └── InputControl.jsx     # Reusable input component
│   ├── App.jsx                  # Root component
│   ├── App.css                  # Tailwind imports
│   └── main.jsx                 # Application entry point
├── index.html
├── package.json
├── yarn.lock
├── vite.config.js
├── postcss.config.js
├── tailwind.config.js
└── .gitignore
```

## 💡 Usage

### Adding an Expense
1. Fill in the expense title, category, and amount
2. Click the "ADD" button
3. The expense will appear in the table below

### Editing an Expense
1. Right-click on any expense row in the table
2. Select "Edit" from the context menu
3. Modify the details in the form
4. Click "ADD" to save changes

### Deleting an Expense
1. Right-click on the expense you want to remove
2. Select "Delete" from the context menu

### Filtering by Category
- Use the dropdown in the "Category" column header
- Select a specific category or "All" to view all expenses

### Sorting Expenses
- Click the up arrow (↑) to sort by amount in descending order
- Click the down arrow (↓) to sort by amount in ascending order

## 🎨 Features Overview

- **Smart Form Validation**: Prevents submission of incomplete data
- **Persistent Storage**: Uses localStorage to save data across sessions
- **Interactive Context Menu**: Right-click functionality for quick actions
- **Dynamic Filtering**: Real-time category filtering
- **Automatic Calculations**: Total expense amount updates automatically

## 🤝 Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 👤 Author

**Kranthi**
- GitHub: [@22kranthi](https://github.com/22kranthi)

## 🙏 Acknowledgments

- Built with React and Vite
- Styled with Tailwind CSS
- Icons: Emoji support

---

⭐ If you found this project helpful, please give it a star!