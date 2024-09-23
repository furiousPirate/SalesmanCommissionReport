Project Description

(Please do open in visual studio code 22)
This project is developed using .NET Core 8 and Angular 17, utilizing ADO.NET for data access. It implements various features and best practices for modern web applications, ensuring a robust, user-friendly experience.

Features
Standard Validations:

All fields are validated according to standard requirements, with custom validation directives implemented for frontend (using reactive forms) and backend validation handled effectively.
Centralized API Error Handling:

Custom middleware is utilized to centralize API error handling on the backend, providing a consistent error management approach across the application.
Lazy Loading of Components:

Components are lazy-loaded as needed, optimizing performance and reducing initial load times through module-based architecture.
Notification and Service Management:

Various services, including a notification service, are created for specific uses in both the frontend and backend, employing dependency injection for better scalability and maintainability.
Guard and Interceptor Implementation:

A route guard is implemented to restrict access, allowing only admin users to make changes, while other users have limited browsing capabilities.
Modules Implemented
Q1: Car Model Management
Brand: Required (Dropdown options: Audi, Jaguar, Land Rover, Renault)
Class: Required (Dropdown options: A-Class, B-Class, C-Class)
Model Name: Required
Model Code: Required (10 alphanumeric characters only)
Description: Required (Using FCK Editor)
Features: Required (Using FCK Editor)
Price: Required
Date of Manufacturing: Required (DateTime)
Active: Boolean
Sort Order: Numeric
Model Images: Required (Max size 5MB, supports multiple image uploads)
Model Listing Features:

Default thumbnail view for model images
Search functionality by Model Name and Model Code
Sorting options by Date of Manufacturing and Sort Order (latest on top)
Q2: Salesman Commission Report
This module calculates the salesman commission report based on the following criteria:

Brand-wise Fixed Commission.
Class-wise Additional % Commission on the model price of the car.
An additional 2% commission on the overall sales amount for salesmen with previous year sales exceeding $500,000, applicable only for Class A cars.
This project aims to provide a comprehensive solution for managing car models and calculating commissions, ensuring all functionalities are seamlessly integrated and user-friendly.
