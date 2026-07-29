# 🏦 Bank Management System

A **Python-based Bank Management System** that uses **MySQL** as its backend database to simulate core banking operations through a command-line interface. The application allows users to create bank accounts, securely log in using an account number and PIN, and perform essential banking transactions such as deposits, withdrawals, and balance inquiries.

This project demonstrates the implementation of **Python programming**, **MySQL database connectivity**, **CRUD operations**, **user authentication**, and **transaction management** while ensuring data integrity through input validation and exception handling.

---

## 🚀 Features

- 🔐 Secure user registration with input validation
- 👤 Automatic generation of unique account numbers and PINs
- 🔑 User authentication using account number and PIN
- 💰 Deposit money into an account
- 💸 Withdraw money with balance validation
- 📊 Check account balance
- 🗄️ MySQL database integration for persistent data storage
- ⚠️ Error handling and validation for reliable transactions

---

## 🛠️ Technologies Used

- **Python 3**
- **MySQL**
- **MySQL Connector/Python**

---

## 📂 Project Structure

```text
Bank-Management/
│── main.py                 # Main application
│── database.py             # Database connection and queries
│── requirements.txt        # Project dependencies
│── README.md               # Project documentation
└── sql/
    └── bank_database.sql   # Database schema
```

> *Note: The structure may vary depending on your project files.*

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/MetalKhamoo/Bank-Management.git
```

### 2. Navigate to the project directory

```bash
cd Bank-Management
```

### 3. Install dependencies

```bash
pip install mysql-connector-python
```

### 4. Create the MySQL database

- Create a new MySQL database.
- Import the provided SQL file (`bank_database.sql`) if available.
- Update your database credentials in the Python source code.

Example:

```python
host="localhost"
user="root"
password="your_password"
database="bank_management"
```

### 5. Run the application

```bash
python main.py
```

---

## 📋 Functionalities

### Account Management

- Create a new bank account
- Generate unique account number and PIN
- Store user information securely

### User Authentication

- Login using account number and PIN
- Validate user credentials

### Banking Operations

- Deposit funds
- Withdraw funds
- Check account balance

---

## 💡 Concepts Demonstrated

- Python Programming
- Object-Oriented Programming (if applicable)
- MySQL Database Connectivity
- CRUD Operations
- User Authentication
- Exception Handling
- Input Validation
- Transaction Processing

---

## 📸 Sample Output

```text
========== BANK MANAGEMENT SYSTEM ==========

1. Create Account
2. Login
3. Exit

Enter your choice: 1

Enter Name:
Enter Age:
Enter Phone Number:
Enter Government ID:
Enter Initial Deposit:

Account Created Successfully!

Account Number: 10023456
PIN: 4728
```

---

## 🔮 Future Enhancements

- Password hashing for improved security
- Money transfer between accounts
- Transaction history
- Admin dashboard
- Interest calculation
- GUI using Tkinter or PyQt
- Web version using Flask or Django
- Email/SMS notifications

---

## 👨‍💻 Author

**Pratham Deepak**

GitHub: https://github.com/MetalKhamoo

---

## 📄 License

This project is intended for **educational and learning purposes**.
