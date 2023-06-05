# FarmerCentralPrototype

ST10081980 PROG7311 POE Part 2

Web Application - Farmer Central Prototype Read Me

This prototype web application is developed using Visual Studio and C# as a demonstration of the Farmer Central system. Farmer Central is a web-based platform that manages farmers and their associated products. It provides user authentication and various 
functionalities for employees and farmers.

Functionality

The prototype web application includes the following functionalities:
User Roles: Two user roles are available - farmer and employee.
User Authentication: Users must log in to access user-specific information.
Add Farmer: Logged-in employees can add a new farmer to the database.
Add Product: Logged-in farmers can add a new product to their profile in the database.
View Product List: Logged-in employees can view the list of all products supplied by a specific farmer.
Filter Product List: Logged-in employees can filter the displayed product list by date range or product type.

Database

The prototype web application uses a SQL Server database to store the data. The database schema consists of the following tables:
Employees: Stores information about employees.
Farmers: Stores information about farmers.
Products: Stores information about the products supplied by farmers.
The database has been created and populated with sample data to demonstrate the functionality of the web application. The initial data includes employees, farmers, and products.

User Interface

The user interface of the prototype web application has been designed to provide a clean and intuitive experience. The pages are responsive and follow modern web design principles. The UI aims to be user-friendly and visually appealing.
Sample Data
The prototype web application includes sample data to demonstrate its functionality. The sample data consists of pre-populated employees, farmers, and products in the database. This data allows you to explore the features of the application without the 
need for manual data entry.

Building and Running the Prototype

Tools Required
- Visual Studio 2022
- .NET Framework (version 4.8 or later)
Getting Started
1. Clone or download the project repository to your local machine.
2. Open the solution file (`FarmerCentralPrototype.sln`) in Visual Studio 2022.
3. Build the Solution:
   - Click on the Build menu in Visual Studio.
   - Select Build Solution (or press F6) to build the solution and resolve any dependencies.
4. Run the Application:
   - Set the `Login.aspx` page as the startup page.
   - Press Ctrl + F5 or click on the Start button in Visual Studio to run the application.
   - The login page should open in your default web browser.
5. Login and Explore:
   - Use the provided login form to enter your credentials.
   - Select the user role (either "Employee" or "Farmer") from the dropdown.
   - Click the "Login" button to proceed.
   - Depending on the selected user role, you will be redirected to either the Employee Page or the Farmer Page.
   - Explore the functionality and features available in each respective page.
  
Additional Notes
- The prototype uses ASP.NET Web Forms for the front-end and C# for the back-end development.
- The project is structured in a modular manner, with separate folders for different components (e.g., Pages, Data Access, Models).
- The database is created automatically when running the application in Visual Studio 2022. It uses a local database file (`FarmCentralDatabase.mdf`) located in the `App_Data` folder.
