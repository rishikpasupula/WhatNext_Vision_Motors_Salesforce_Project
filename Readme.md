Overview
This project automates vehicle order processing for a fictional automobile company using Salesforce. Developed as part of SmartBridge Salesforce Virtual Internship Project, it leverages Salesforce custom objects, flows, and Apex to streamline dealer assignments, stock management, test drive scheduling, and service requests.

Features
• Automated assignment of vehicle orders to the nearest dealer based on customer location.
• Stock validation preventing orders for out-of-stock vehicles.
• Scheduled email reminders for test drives.
• Custom Salesforce Lightning App for unified management.
• Apex triggers and batch classes for advanced business logic and inventory updates.

Technology Stack
• Salesforce CRM: Cloud platform for CRM and automation.
• Custom Objects: Represent Vehicles, Dealers, Customers, Orders, Test Drives, and Service Requests.
• Tabs: For easy access to custom objects.
• Lightning App: A custom app consolidating all functionalities.
• Flows: Point-and-click automation for dealer assignment and email reminders.
• Apex Code: Custom triggers and batch processing ensuring business rules and data integrity.

Execution Summary
• Setup Salesforce Developer Org.
• Designed data model with six custom objects.
• Created tabs and a Lightning App for organized UI.
• Built Flows for automating dealer assignment and test drive reminders.
• Developed Apex triggers and batch jobs for stock management.
• Tested with sample records demonstrating end-to-end workflow.

Sample Workflow
• A customer places an order with location data.
• The system automatically assigns the closest dealer.
• Stock is verified; orders are blocked if unavailable.
• Customer books a test drive and receives automated reminders.
• Post-sale, customers can log service requests with automated updates.

Future Enhancements
• Integration with email/SMS gateways and mapping APIs.
• AI-driven recommendations and pricing strategies.
• Enhanced dashboards and mobile interfaces.

This project demonstrates Salesforce capabilities in automating real-world sales and service processes for a vehicle retailer.
