# Retail Plus – Inventory Management System

## Overview

Retail Plus is a Python-based inventory management system designed for small retail businesses. It digitalises traditional inventory management processes, allowing staff to manage product records, monitor stock levels, track supplier orders and generate monthly inventory reports through a command-line interface (CLI).

## Key Features

- **User Registration and Login** – Account creation and credential verification.
- **Product Management** – Add, view, search, edit and delete product records.
- **Inventory Sorting** – Sort products by category, name, price, stock quantity and promotion status.
- **Product Searching** – Search products by ID, category, name, promotion status and stock level.
- **Automatic Stock Classification** – Categorise products into out-of-stock, low, medium and high stock levels.
- **Inventory Ordering** – Manage supplier information, inventory orders and order statuses.
- **Order Export** – Generate individual or multiple inventory order records in text files.
- **Monthly Reporting** – Generate inventory statistics and summaries to support business decision-making.
- **Input Validation and Exception Handling** – Handle invalid inputs and file operation errors.

## Technologies Used

| Technology | Purpose |
|---|---|
| Python | Core application development |
| Pandas | Data manipulation, searching and sorting |
| OpenPyXL | Excel file operations |
| Microsoft Excel | Inventory and order data storage |
| Text Files | User records and report generation |

## Technical Implementation

- Modular programming
- CRUD operations
- Data manipulation and analysis
- File handling and persistent data storage
- Exception handling
- Input validation
- Automatic identifier generation
- Rule-based stock classification

## Repository Structure

| File | Description |
|---|---|
| `menu.py` | Main application entry point and menu navigation |
| `register.py` | User account registration |
| `login.py` | User login and credential verification |
| `add_product.py` | New product registration |
| `view_product.py` | Inventory display and sorting |
| `search_product.py` | Multi-criteria product searching |
| `edit_product.py` | Product information updates |
| `delete_product.py` | Product record deletion |
| `inventory_ordering_system.py` | Inventory order management |
| `print_inventory_ordering_system.py` | Inventory order export |
| `generate_report.py` | Monthly inventory report generation |
| `RetailPlus.xlsx` | Product inventory and order records |
| `user_info.txt` | Local user account records |
| `Report.pdf` | Detailed project documentation |

## Getting Started

### Prerequisites

- Python 3
- Pandas
- OpenPyXL

### Installation and Execution

1. Clone or download this repository.
2. Install the required Python libraries:

   `pip install pandas openpyxl`

3. Ensure `RetailPlus.xlsx` is located in the project directory.
4. Run the main application:

   `python menu.py`

5. Register a new account or log in to access the inventory management system.

## Individual Contributions – Yew Kai Qian

- Developed the View Current Inventory module with multiple sorting options.
- Developed the Search Product module with multiple search criteria.
- Co-developed the Add New Product module, incorporating automatic product ID generation and stock-level classification.
- Contributed to product input validation and exception handling.
- Co-developed the user registration module with credential validation and text file handling.

## Contributors

- Chan Yi Yang
- Leong Di Hao
- Liew Jia Min
- Yew Kai Qian

## Project Documentation

Refer to the [Project Report](Report.pdf) for detailed documentation, including:

- Problem statements and project objectives
- System design and implementation
- Source code explanations
- Application outputs
- Input validation and testing
- Advanced programming concepts
- Individual contributions

## Project Background

This project was developed collaboratively by four undergraduate students at Universiti Tunku Abdul Rahman (UTAR) as part of the Introduction to Business Programming coursework.

- **Course:** UCCB1104 – Introduction to Business Programming
- **Trimester:** June 2025
- **Project Type:** Academic Group Project

## Project Limitations and Future Improvements

The current implementation is an academic prototype that uses Excel and text files for local data storage.

Potential future improvements include:

- Relational database integration
- Password hashing and improved authentication
- Graphical user interface (GUI)
- Enhanced inventory analytics and visualisation
- Low-stock notifications
- Multi-user access support
