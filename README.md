## Inventory_Management_System
Basic Inventory Management System using python and json.

This is a basic menu driven system that lets the user to manage their inventory.

The **inventory_records.json** is where all the records are stored.


The **Inventory_Management.ipynb** file allows the user to perform various functionalities like:

1) adding products to the inventory
2) viewing them
3) updating them
4) know the quantity/stocks of any specific products. 
5) Knowing the sales.(This would actually return a list of all the sales that has happened for a specific id with date, the quantity bought by the user, the stock left, and the total amount in that particular sale.)

All the changes would be reflected in the records.json


The **Sales.ipynb** file lets the user to:
1) Buy a certain product
2) Viewing the list of all the items.
3) Generating bill. 

All the details of the sale gets updated in **sales_records.json**

Please note that all the valid id for the data stored in the current json files for any product is a three- digit number that starts from 101. 
