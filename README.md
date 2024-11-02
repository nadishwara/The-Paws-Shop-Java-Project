Pet Supply Store Management System - Java Project
Project Overview

This project is a Java-based management system for a pet supply store, developed as part of a university assignment. The system streamlines store operations by automating inventory management, user access control, and supplier handling. This project emphasizes object-oriented programming principles and demonstrates role-based access control.
Features

    User Login and Role-Based Access:
        Cashier: View and manage products, assist with customer purchases.
        Manager: Access all cashier functions plus manage suppliers and cashier accounts.
    Product and Inventory Management: Organize products into categories (e.g., toys, food, grooming items).
    Supplier Management: Managers can add, view, and update supplier information.
    Purchase and Payment Processing: Supports cash-on-delivery and online payment with OTP verification for added security.

System Requirements

    Java Development Kit (JDK): Version 8 or higher
    Java IDE: (NetBeans, Eclipse, or IntelliJ recommended)
    Git: For version control (optional, but recommended)

Setup and Installation

    Clone the Repository:

    bash

    git clone https://github.com/username/pet-supply-store-management.git

    Open in Java IDE: Import the project in your preferred Java IDE.
    Build and Run: Compile and run the project to explore its features.

User Roles and Functionalities
Cashier

    View Products: Access detailed information on all products and categories.
    Add Products: Add new products to the inventory with appropriate categories.
    Process Purchases: Assist customers with purchasing products.

Manager

    Manage Users: Create new accounts for cashiers.
    Supplier Management: Add, view, and update supplier details for better stock management.

System Architecture

The project is structured with core Java classes that reflect the object-oriented approach, including classes for User, Product, Supplier, and Purchase. Managers and cashiers interact with the system based on their specific roles, ensuring controlled access.
UML Diagrams

For detailed architecture and design, refer to the UML diagrams included in the docs/ folder:

    Class Diagram: Shows the relationships between main classes.
    ER Diagram: Outlines database entities and relationships.

Future Enhancements

    Inventory Tracking: Add low-stock notifications and automated reordering.
    Reporting: Include sales reports and inventory summaries for managers.
    Enhanced Security: Implement additional user verification steps for sensitive actions.

Contributing

Contributions are welcome! Please fork the repository, create a new branch, and submit a pull request.
