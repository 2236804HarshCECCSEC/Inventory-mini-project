📦 Inventory Management System (Python - OOP Based)
📌 Project Overview

This project is a console-based inventory management system built using Python.
It helps store and manage product details like name, price, and quantity.

The system has two types of users:

👨‍💼 Admin (Full control)

👨‍🔧 Staff (Limited control)

It works in the terminal/command prompt.

🚀 Features (Explained in Simple Words)
🔐 Role-Based Access

The system asks who you are (Admin or Staff).

Based on your role, it shows different options.

This keeps the system secure and organized.

👨‍💼 Admin Capabilities (Full Control)
➕ Add New Product

Admin can enter:

Product name

Price

Quantity
This adds a new item to inventory.

✏️ Update Product Details

Admin can change:

Product price

Product quantity
Useful when price changes or new stock arrives.

❌ Delete Product

Admin can remove a product completely from the inventory.

📋 View All Products

Admin can see the complete list of all products with their details.

📦 Manage Stock

Admin can increase stock when new items arrive.

👨‍🔧 Staff Capabilities (Limited Control)
👀 View Products

Staff can see available products and their stock.

🛒 Sell Product

When a product is sold:

Staff selects the product

Quantity is reduced automatically

🔄 Auto Stock Update

After selling, the system updates the remaining quantity.

🛠️ Technologies Used (Simple Explanation)

Python 3 → Main programming language

OOP (Object-Oriented Programming) → Used classes to organize code

Loops → To repeat menu options

Conditional Statements (if-else) → To check roles and conditions

Exception Handling → To avoid crashes when user enters wrong input

🧠 OOP Concepts Used (Simple Meaning)
📦 Class

Blueprint to create objects (like Product class).

🏷️ Object

Real item created from class (like a specific product).

🔧 Constructor (__init__)

Runs automatically when object is created.

🔒 Encapsulation

Keeping data and functions together inside a class.

⚠️ Exception Handling

Using try-except to handle errors safely.

⚙️ System Workflow (Step-by-Step Explanation)
1️⃣ Program Starts

The system begins running in terminal.

2️⃣ Role Selection

User selects:

1 for Admin

2 for Staff

3️⃣ Login (If implemented)

User enters credentials.

4️⃣ Menu Display

Based on role:

Admin menu shows full options

Staff menu shows limited options

5️⃣ User Chooses Operation

User selects what they want to do:

Add product

Sell product

Update stock

View products

6️⃣ System Processes Request

The program:

Updates data

Shows confirmation message

7️⃣ Loop Continues

Menu appears again until user chooses Exit.

8️⃣ Exit

Program stops.

📂 Project Structure
Inventory Management System
│
├── inventory.ipynb   # Main project file
└── README.md         # Project documentation

▶️ How to Run
Method 1: Jupyter Notebook
jupyter notebook


Open inventory.ipynb
Click Run All Cells

Method 2: Convert to Python File
jupyter nbconvert --to script inventory.ipynb
python inventory.py

📈 Future Improvements

Add database (MySQL / SQLite)

Add GUI interface

Add sales report feature

Deploy as web app

Add authentication system

🎯 What I Learned

How real inventory systems work

How to structure projects using OOP

How to handle user input errors

How to create role-based systems

👨‍💻 Author

Harsh Singh
