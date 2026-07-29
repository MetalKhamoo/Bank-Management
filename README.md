# 🏦 Bank Management System

A **Python-based command-line Bank Management System** that uses **MySQL** to store customer account information and perform basic banking operations. The application allows users to create new bank accounts, log in with a randomly generated account number and PIN, and perform common banking activities such as checking account balances, depositing money, and withdrawing funds.

The project demonstrates the use of **Python programming**, **MySQL database connectivity**, **input validation**, **conditional statements**, **loops**, **random number generation**, and **basic database operations**. Customer information is stored in a MySQL database, while transactions are managed through a simple and interactive command-line interface.

---

## 🚀 Features

- Create a new bank account
- Automatic generation of account number and PIN
- Secure login using account number and PIN
- Deposit money into an account
- Withdraw money with balance validation
- Check current account balance
- Store customer information in a MySQL database
- Input validation for user details

---

## 🛠️ Technologies Used

- Python
- MySQL
- MySQL Connector/Python

---

## 📂 Project Structure

```text
Bank-Management/
│── bank management.py
└── README.md
```

---

## ⚙️ Prerequisites

Before running the project, ensure you have:

- Python 3.x installed
- MySQL Server installed and running
- mysql-connector-python package installed

Install the required package using:

```bash
pip install mysql-connector-python
```

---

## ▶️ Running the Project

1. Clone the repository.

```bash
git clone https://github.com/MetalKhamoo/Bank-Management.git
```

2. Navigate to the project directory.

```bash
cd Bank-Management
```

3. Update the MySQL connection credentials inside the Python file if required.

```python
host="localhost"
user="root"
password="your_password"
```

4. Run the application.

```bash
python "bank management.py"
```

---

## 📋 Functionalities

### Account Creation

- Enter personal details
- Initial deposit
- Automatically generated account number and PIN
- Customer details stored in MySQL

### User Login

- Login using account number and PIN
- Authentication before accessing banking services

### Banking Operations

- Check account balance
- Deposit money
- Withdraw money
- Return to homepage or exit the application

---

## 💻 Database

The application automatically creates:

- Database: `bank`
- Table: `B_Details`

The table stores:

- Name
- Age
- Phone Number
- Initial Deposit
- Government ID
- Account Number
- PIN

---

## 📚 Concepts Used

- Python Programming
- MySQL Database Connectivity
- CRUD (Create and Read)
- User Authentication
- Conditional Statements
- Loops
- Input Validation
- Random Number Generation
- Exception-Free User Interaction

---

## 🔮 Future Improvements

- Update customer details
- Delete account functionality
- Transaction history
- PIN change option
- Money transfer between accounts
- Interest calculation
- Password encryption
- Graphical User Interface (GUI)
- Online banking support

---

## 👨‍💻 Author

**Pratham Deepak**

GitHub: https://github.com/MetalKhamoo

---

## 📄 License

This project is developed for educational and learning purposes.
