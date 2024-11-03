<h1>Pet Supply Store Management System - Java Project</h1>

<h2>Project Overview</h2>

<P>This project is a Java-based management system for a pet supply store, developed as part of a university assignment. The system streamlines store operations by automating inventory management, user access control, and supplier handling. This project emphasizes object-oriented programming principles and demonstrates role-based access control.</P>


<h3>Features</h3>
<b>User Login and Role-Based Access:</b> </br>
</br>

<b>Cashier:</b> View and manage products, assist with customer purchases.      
<b>Manager:</b> Access all cashier functions plus manage suppliers and cashier accounts.</br>
<b>Product and Inventory Management:</b> Organize products into categories (e.g., toys, food, grooming items).</br>
<b>Supplier Management:</b> Managers can add, view, and update supplier information.</br>
<b> Purchase and Payment Processing:</b> Supports cash-on-delivery and online payment with OTP verification for added security.</br>

System Requirements

    Java Development Kit (JDK): Version 8 or higher
    Java IDE: (NetBeans, Eclipse, or IntelliJ recommended)
    Git: For version control (optional, but recommended)

<b>Setup and Installation</b></br>

Clone the Repository:

    bash

    git clone https://github.com/username/pet-supply-store-management.git

<p><b>Open in Java IDE:</b> Import the project in your preferred Java IDE.</br>
<b>Build and Run:</b> Compile and run the project to explore its features.
</p>
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
