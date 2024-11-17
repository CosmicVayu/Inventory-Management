# Inventory Management System

## Description

The *Inventory Management System* is designed to help small to medium businesses track and manage their inventory in real-time. It allows users to add, update, remove, and view products, ensuring efficient stock management and avoiding overstocking or stockouts.

## Table of Contents
- [Description](#description)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)

## Features
- Add, update, and delete products in the inventory.
- Track stock levels and update inventory in real time.
- The employee management system works inside the inventory.
- Generate reports on sales, and reorder levels.

## Installation

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/CosmicVayu/inventory-management.git
   ```
2. Navigate to the project directory:
   ```bash
   cd inventory-management
   ```
3. Set up the database (if applicable):
   - Import the provided `inventory_management.sql` file to your MySQL database.
---

## Usage


1. Open the application in your web browser by navigating to `http://localhost:3300`.

<img width="782" alt="Screenshot 2024-11-17 at 10 48 49 AM" src="https://github.com/user-attachments/assets/f24ccabe-15be-434f-aa07-4942054fbe7c">

2. Login with your admin credentials:
   - Username: `manager@gmail.com`
   - Password: `manager123`
     
3. Click on the button you want to use for example Product, Supplier, Sales, etc.
   <img width="838" alt="Screenshot 2024-11-17 at 10 49 44 AM" src="https://github.com/user-attachments/assets/e2a41c01-09be-41c2-b41c-5e93333308e4">

4. Once logged in, you can start managing the inventory by:
   - Adding new products
   - Viewing product details
   - Generating stock reports
<img width="777" alt="Screenshot 2024-11-17 at 10 50 57 AM" src="https://github.com/user-attachments/assets/177ee22b-c02a-453b-b448-10b873a398d9">

5. Manage Employees using this window panel. You can search, add,delete, etc. using this window.
<img width="891" alt="Screenshot 2024-11-17 at 10 51 17 AM" src="https://github.com/user-attachments/assets/a95c0e98-2064-4d98-ba49-e0f0e6e8d211">

6. Use this window panel to manage suppliers. You can see from whom you are taking the product.
<img width="889" alt="Screenshot 2024-11-17 at 10 51 46 AM" src="https://github.com/user-attachments/assets/d3a721b4-1d04-4c21-a246-05030ebb3c8b">

7. Orders window table: From here, you can order products from suppliers, which will be updated directly in MySQL.
<img width="893" alt="Screenshot 2024-11-17 at 11 14 17 AM" src="https://github.com/user-attachments/assets/2e2ba1af-829b-4daf-b13f-c1396e3fa76b">

8. The sales window evaluates the total sold items and bought items and analyses the profit and loss.<img width="895" alt="Screenshot 2024-11-17 at 12 03 59 PM" src="https://github.com/user-attachments/assets/281ab8f4-09e3-411c-984d-867495d17af7">



## Contributing

1. Fork the repository.
2. Create your feature branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Make your changes and commit them:
   ```bash
   git commit -m 'Add new feature'
   ```
4. Push to your branch:
   ```bash
   git push origin feature/your-feature-name
   ```
5. Open a pull request to the main branch for review.

