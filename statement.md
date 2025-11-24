# Project Statement: Grocery Store Billing System

## Problem Statement
In many small-scale retail environments and local grocery stores, billing is often performed manually or using basic calculators. This manual process is prone to human error, such as incorrect summation of prices or miskeyed entries. Furthermore, manual billing is time-consuming, leading to longer queues and customer dissatisfaction. There is a need for a lightweight, automated solution that ensures calculation accuracy and provides a clear, readable receipt for the transaction.

## Scope of the Project
The scope of this project is to develop a text-based Command Line Interface (CLI) application using Python. The system focuses on the immediate checkout process for a single customer session. 

**In Scope:**
* Accepting dynamic user input for item names and prices.
* Validating numeric input to prevent application crashes during data entry.
* Real-time storage of item details in temporary data structures (lists).
* Automated calculation of the grand total.
* Generation of a formatted textual receipt.

**Out of Scope:**
* Persistent database storage (inventory management).
* Graphical User Interface (GUI).
* Integration with physical hardware (barcode scanners/printers).

## Target Users
* **Small Business Owners:** Owners of local kirana stores or convenience shops looking for a digital upgrade from pen-and-paper billing.
* **Cashiers/Counter Staff:** Individuals responsible for rapid checkout processing who require a tool to minimize calculation errors.
* **Python Learners:** Students and developers looking for a practical demonstration of list manipulation, loops, and exception handling in Python.

## High-Level Features
1.  **Dynamic Transaction Handling:** The system adapts to the size of the customer's basket, allowing the user to define the number of items per transaction dynamically.
2.  **Robust Input Validation:** Implements exception handling (Try/Except blocks) to ensure that the system remains stable even if the user inputs invalid data types (e.g., text instead of currency).
3.  **Automated Financial Calculation:** Eliminates mental math by automatically summing item prices to produce an accurate total bill amount.
4.  **Professional Receipt Generation:** Produces a structured, aligned output summary that lists items alongside their specific costs, improving transparency for the customer.
