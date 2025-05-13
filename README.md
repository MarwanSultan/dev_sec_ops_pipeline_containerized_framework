# 🏦 Mock Banking Test Framework

A lightweight Python framework that simulates a banking environment using SQLAlchemy, Faker, and Pytest to test SQL transactions, generate synthetic data, and validate business logic through automated tests.

## 📚 Overview

This project models a simplified banking system with `Customers` and `Transactions`, allowing testers and developers to:

- Generate large datasets with realistic-looking customer and transaction records.
- Run automated tests to validate SQL queries, database integrity, and edge cases.
- Experiment with fraud detection logic (optional AI support).

## 🚀 Features

- **Mock Schema**: Customers and Transactions tables with ORM relationships.
- **Data Generation**: Faker-powered creation of thousands of records.
- **Automated Testing**: Pytest-based test suite for validating data and SQL behavior.
- **Fraud Detection Test**: Optional tests to detect suspicious financial activity.
- **Simple DB Config**: SQLite by default, extensible to PostgreSQL, MySQL, etc.

## 🛠️ Technologies Used

- Python 3.10+
- SQLAlchemy
- Pytest
- Faker
- SQLite

## 📂 Project Structure

## Prepare the test environment

# Navigate to the project directory
cd sql_pytest_demo

# Create a virtual environment named `.venv`
python3 -m venv .venv

# Activate the virtual environment
source .venv/bin/activate


## 🧪 Running Tests

1. **Install dependencies**  
   ```bash
   pip install -r requirements.txt

2. **Run the tests**
    pytest
