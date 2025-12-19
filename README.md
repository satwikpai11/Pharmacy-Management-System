Pharmacy Management System - Project from Undergrad.

Overview

The Pharmacy Management System is a Java-based desktop application developed using JavaFX and SQLite.
It is designed to manage basic pharmacy operations such as user authentication, medicine inventory management, and billing through an interactive graphical user interface.

This project demonstrates the integration of a GUI application with a relational database and implements core CRUD (Create, Read, Update, Delete) operations.

⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻

Technologies Used
	•	Java
	•	JavaFX (FXML for UI design)
	•	SQLite (Embedded Database)
	•	JDBC (Database Connectivity)

⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻

Features

1. User Authentication
	•	Login system using username and password
	•	Credentials verified using SQLite database

2. Medicine Stock Management
	•	Add new medicines
	•	Update medicine quantity
	•	Delete medicines from inventory
	•	View available stock using JavaFX tables

3. Billing System
	•	Select medicines from stock
	•	Generate customer bills
	•	Calculate total cost
	•	Store order details in the database

4. Database Integration
	•	Uses SQLite for persistent storage
	•	JDBC for database operations
	•	Supports insert, update, delete, and fetch operations

⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻

How to Run the Project

Prerequisites
	•	Java JDK 8 or above
	•	JavaFX properly configured
	•	SQLite JDBC driver (if not bundled)

Steps
	1.	Clone the repository.
    2.	Open the project in an IDE (IntelliJ IDEA / Eclipse / NetBeans).
	3.	Ensure JavaFX is configured correctly.
	4.	Run Login.java to start the application.

⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻

Database
	•	The project uses an embedded SQLite database
	•	Database file: res/test.db
	•	Tables store:
	•	User login credentials
	•	Medicine stock details
	•	Billing/order records

⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻

Use Case

This system can be used as:
	•	A college mini project
	•	A demonstration of JavaFX + database integration
	•	A foundation for building a larger pharmacy or inventory management system

⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻

Limitations
	•	Passwords are stored in plain text (not secure for production)
	•	Single-user desktop application
	•	No role-based access control
	•	Not designed for large-scale or multi-user deployment

⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻

Future Enhancements
	•	Password encryption and role-based login
	•	Sales reports and analytics
	•	Expiry date tracking for medicines
	•	Multi-user support
	•	Export bills as PDF

⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻
