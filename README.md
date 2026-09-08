# Techify

Techify is an ASP.NET MVC E-commerce platform that allows users to browse products, manage their cart, place orders, and leave reviews. It supports distinct roles for Customers, Sellers, and Administrators.

## Features
- **User Roles:** Customers, Sellers, and Admins.
- **Product Catalog:** Browse products by categories and brands.
- **Shopping Cart & Checkout:** Add products to the cart and securely complete orders.
- **Reviews & Ratings:** Customers can review products they purchased.
- **Order Management:** Tracking and management of orders for customers and sellers.

## Tech Stack
- **Framework:** .NET Framework 4.7.2
- **Architecture:** ASP.NET MVC
- **Database:** SQL Server
- **ORM:** Entity Framework 6.2.0
- **Frontend:** HTML, CSS, Bootstrap 5, jQuery

## Database Setup
The database schema can be created using the included SQL script: `-- Database techify.txt`.
Execute this script in your SQL Server instance to create the necessary tables and relationships.

## Local Setup
1. Clone the repository.
2. Open the `Techify.sln` solution in Visual Studio.
3. Restore NuGet packages.
4. Update the connection string in `Web.config` to point to your local SQL Server instance.
5. Build and run the solution.
