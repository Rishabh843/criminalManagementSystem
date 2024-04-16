# 🕵️‍♂️ Criminal Management System

A Python application for managing criminal records efficiently.

## 🚀 Features

- **CRUD Operations:** Add, update, delete, and search criminal records.
- **User-friendly UI:** Graphical interface for easy navigation.
- **Database Integration:** MySQL database for storing criminal data.

## 📦 Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/Rishabh843/criminalManagementSystem.git
    ```

2. **Install Dependencies:**

    ```bash
    pip install pillow mysql-connector-python
    ```

3. **Set Up Database:**

    - Create a MySQL database named `management`.
    - Run the provided SQL script (`database_setup.sql`) to create the necessary table (`criminal1`) in the database.

4. **Update Database Connection:**

    - Open the `criminal_management_system.py` file.
    - Modify the database connection parameters (host, username, password) as per your MySQL configuration.

5. **Run the Application:**

    ```bash
    python criminal_management_system.py
    ```

## ⚠️ Note about Python Version

This project was developed using Python 3.10. While it should work smoothly on other Python versions as well, it's recommended to use Python 3.10 to ensure compatibility.
