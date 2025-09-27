# PL-Kits Management System

[![Python](https://img.shields.io/badge/python-v3.7+-blue.svg)](https://www.python.org/downloads/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Platform](https://img.shields.io/badge/platform-Windows%20%7C%20macOS%20%7C%20Linux-lightgrey)](https://github.com/yourusername/pl-kits-management)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/yourusername/pl-kits-management/graphs/commit-activity)

A comprehensive management system consisting of two powerful applications: **Budget Calculator** and **Inventory Management System**. Built with Python, featuring modern GUI interfaces and robust database functionality.

## 🌟 Features

### Budget Calculator (Question 1)
- 📊 **Tax Calculation**: Automatic South African tax bracket calculations
- 💰 **Expense Tracking**: Smart categorization of monthly expenses
- 📈 **Visual Progress Bars**: Interactive expense visualization
- 🖥️ **Modern GUI**: Clean Tkinter-based interface
- 📱 **Responsive Design**: Centered windows and user-friendly dialogs

### Inventory Management System (Question 2)
- 🏪 **Product Management**: Add, remove, update, and display products
- 💾 **SQLite Database**: Persistent data storage
- 🛒 **Sales Tracking**: Complete sales transaction management
- 📊 **Real-time Inventory**: Automatic quantity updates
- ⚡ **Error Handling**: Comprehensive validation and error management

## 🚀 Quick Start

### Prerequisites
- Python 3.7 or higher
- tkinter (usually comes with Python)
- sqlite3 (built-in with Python)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/pl-kits-management.git
   cd pl-kits-management
   ```

2. **No additional dependencies required!** The project uses only Python standard library modules.

### Running the Applications

#### Budget Calculator
```bash
# Navigate to project directory and run:
python -c "exec(open('Question1.ipynb').read())"
```
Or open `Question1.ipynb` in Jupyter Notebook and run all cells.

#### Inventory Management System
```bash
# Navigate to project directory and run:
python -c "exec(open('Question2.ipynb').read())"
```
Or open `Question2.ipynb` in Jupyter Notebook and run all cells.

## 📖 Usage

### Budget Calculator Usage

1. **Launch the application**
2. **Click "Create New Entry"**
3. **Enter your user code**
4. **Input your gross monthly income**
5. **View detailed budget breakdown with:**
   - Income before and after tax
   - Categorized expenses with progress bars
   - Net income calculations

#### Expense Categories:
- **Utilities**: 5% of net income
- **Rent/Housing**: 15% of net income  
- **Transportation**: 30% of net income
- **Healthcare**: 3% of net income
- **Groceries**: 10% of net income
- **Communication**: 2% of net income

### Inventory Management Usage

1. **Launch the application**
2. **Choose from the menu options:**
   - `1` - Add a new product
   - `2` - Remove a product by ID
   - `3` - Update existing product details
   - `4` - Display all products in inventory
   - `5` - Process a sale transaction
   - `6` - Exit the application

#### Database Schema:
```sql
-- Products Table
Product (
    product_id INTEGER PRIMARY KEY,
    product_name TEXT NOT NULL,
    product_price REAL NOT NULL,
    product_quantity INTEGER NOT NULL
)

-- Sales Table
Sales (
    sale_id INTEGER PRIMARY KEY,
    sale_date TEXT NOT NULL,
    product_name TEXT NOT NULL,
    sale_total REAL NOT NULL
)
```

## 🏗️ Project Structure

```
📦 pl-kits-management/
├── 📄 Question1.ipynb          # Budget Calculator Application
├── 📄 Question2.ipynb          # Inventory Management System  
├── 📄 README.md               # Project documentation
├── 📄 LICENSE                 # MIT License
└── 📄 inventory.db            # SQLite database (auto-created)
```

## 🛠️ Technical Details

### Technologies Used
- **Python 3.7+**: Core programming language
- **Tkinter**: GUI framework for Budget Calculator
- **SQLite3**: Database engine for Inventory Management
- **datetime**: Date handling for sales records

### Key Classes

#### Budget Calculator
- `BudgetCalculation`: Core calculation logic
- `BudgetUI`: Main GUI interface
- `CustomInputDialog`: Custom dialog windows

#### Inventory Management
- `Store`: Database operations and business logic

## 🤝 Contributing

1. **Fork the Project**
2. **Create your Feature Branch** (`git checkout -b feature/AmazingFeature`)
3. **Commit your Changes** (`git commit -m 'Add some AmazingFeature'`)
4. **Push to the Branch** (`git push origin feature/AmazingFeature`)
5. **Open a Pull Request**

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Ndaedzo Mudau**
- Student ID: 7120

## 🙏 Acknowledgments

- Built as part of ITAPA2-12 Project
- University of Pretoria - 2022
- Special thanks to the Python community for excellent documentation

## 📊 Project Stats

![GitHub repo size](https://img.shields.io/github/repo-size/yourusername/pl-kits-management)
![GitHub last commit](https://img.shields.io/github/last-commit/yourusername/pl-kits-management)
![GitHub issues](https://img.shields.io/github/issues/yourusername/pl-kits-management)

---

<div align="center">
  <strong>⭐ Star this repository if you found it helpful!</strong>
</div>
