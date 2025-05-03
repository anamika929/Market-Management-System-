# Market-Management-System-

Here are my teammates_

https://github.com/sabiharummanmedha

https://github.com/Intajnibir

 Summary of Market Management System Code

This C++ program implements a simple market management system that allows users to track and manage product inventory. Here are the key features:

 Core Components:
- Product Class: Represents items with attributes like serial number, name, size, price, quantity, and expiry date.
- File Storage: All product data is stored in "Product.txt" with a simple text format.

 Main Functionalities:
1. Product Management:
   - Add new products with full details
   - View all available products
   - Search products by serial number and size
   - Edit existing product information
   - Delete products from inventory

2. Sales Features:
   - Sell products (reduces quantity, records transaction)
   - View selling history with timestamps

3. **Inventory Tracking:
   - Count total number of products in stock
   - Track product quantities and automatically remove items when stock reaches zero

 Implementation Details:
- Uses file I/O operations to persist data between sessions
- Implements a simple text-based menu system
- Includes date/time tracking for sales records
- Handles basic error cases (product not found, insufficient quantity)

The program provides a complete solution for small-scale inventory management with sales tracking capabilities, all through a console interface.
