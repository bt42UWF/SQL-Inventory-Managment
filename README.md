# SQL Practice Code Example
### Creating and managing an inventory database. 

This code is creating a SQL database structure for inventory management, populating it with sample data, and performing various operations such as selecting, updating, deleting, and altering data within the database.

Here's a breakdown of what each part does:

1. **Table Creation:** Defines a table named Inventory with columns for product information such as ProductID, ProductName, Quantity, Price, Category, ExpDate, and Manufacturer.

2. **Data Insertion:** Inserts sample data into the Inventory table.

3. **Data Selection:** Retrieves all data from the Inventory table, then retrieves a count of products grouped by their manufacturer, and selects specific data based on the category.

4. **Data Deletion and Update:** Deletes a specific product from the inventory (ProductID = 4) and updates the quantity of a product (Smartphone) to 25.

5. **Altering Table:** Adds a new column StockLocation to the Inventory table.

6. **Updating Data in the New Column:** Updates the StockLocation for each product.

7. **Transaction Handling:** Begins a transaction, updates the quantity and price of a specific product (ProductID = 1), and commits the transaction.

8. **Transaction Check:** Verifies if the transaction was successful by selecting the data for the product whose details were updated.

9. **Expiry Check:** Retrieves products that are going to expire within the next 3 months.

