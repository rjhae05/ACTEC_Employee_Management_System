🧩 Models/

Description:
This folder contains all data models and DTOs (Data Transfer Objects) that represent the structure of data used throughout the application.
Each model defines the properties and data types of entities like Users, Products, Orders, etc., ensuring consistent data handling between the UI, Database, and Services.

Purpose:

Represent data as objects instead of raw database rows or JSON strings.

Improve code clarity and maintainability by defining a single structure for each entity.

Facilitate data binding in WinForms (e.g., showing model data in DataGridView or TextBoxes).

Enable object-oriented manipulation of application data.

Typical Contents:

File			Description
User.vb		| Represents user information such as ID, Name, Email, and Password.
Product.vb	| Defines product attributes like ID, ProductName, Price, and Stock.

Best Practices:

Use Properties (Public Property) instead of public fields for better encapsulation.

Keep models lightweight — avoid putting business logic here.

Map model properties directly to database columns or API JSON fields.