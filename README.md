billing_grocery
# Grocery Store Billing System

## Overview of the Project
The **Grocery Store Billing System** is a Python-based Command Line Interface (CLI) application designed to automate the billing process for small shops or checkout counters. It allows users to input a dynamic list of grocery items and their prices, validates the input to prevent errors, and generates a formatted bill receipt showing individual item costs and the grand total.

## Features
* **Dynamic Item Entry:** Users can specify exactly how many items they wish to bill.
* **Input Validation:** The system includes error handling to ensure prices are entered as numbers. If a user enters text (e.g., "ten") instead of a number, the system catches the error and prompts for input again.
* **Formatted Receipt:** Generates a clean, professional text-based receipt with the Item Name and Price side-by-side.
* **Currency Formatting:** Automatically displays prices with two decimal places (e.g., ₹50.00).
* **Total Calculation:** automatically sums the cost of all items.

## Technologies/Tools Used
* **Programming Language:** Python 3.x
* **Libraries:** Standard Python Library (No external installations required)
* **IDE/Editor:** Compatible with VS Code, PyCharm, Jupyter Notebook, or any standard text editor.

## Steps to Install & Run the Project

1.  **Prerequisites:**
    Ensure you have Python installed on your system. You can check this by running:
    ```bash
    python --version
    ```

2.  **Installation:**
    Download the `billing_system.py` file or copy the source code into a file named `billing_system.py`.

3.  **Running the Application:**
    Open your terminal or command prompt, navigate to the folder containing the file, and run the following command:
    ```bash
    python billing_system.py
    ```

## Instructions for Testing
To verify the application is working correctly, perform the following test cases:

**Test Case 1: Standard Input**
1.  Run the program.
2.  Enter number of items: `2`
3.  Enter Item 1: `Milk`, Price: `30`
4.  Enter Item 2: `Bread`, Price: `45.5`
5.  **Expected Output:** A receipt listing both items and a Total Bill of ₹75.50.

**Test Case 2: Error Handling (Invalid Price)**
1.  Run the program.
2.  Enter number of items: `1`
3.  Enter Item 1: `Sugar`
4.  Enter Price: `Expensive` (Type text instead of a number)
5.  **Expected Output:** The system should print "Invalid price" and ask you to enter the price again. Once a valid number is entered, the bill should generate normally.
