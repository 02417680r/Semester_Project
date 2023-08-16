# Semester_Project
Abubakari Rafiatu
UEB3252922
Project description
 Inventory System
The code you provided is an example of an inventory system program implemented in C++. It allows the user to perform various operations on a list of products. Here's a breakdown of how the code works:

The Product class defines the attributes and methods associated with a product. Each product has a name, price, and quantity. Methods like displayDetails(), updateDetails(), getPrice(), and getName() allow you to interact with and manipulate product data.

The main() function is where the program's execution starts. It initializes an empty vector called inventory to hold the products.

Inside a loop that runs indefinitely (controlled by while (true)), the user is presented with a menu of options:

Option 1: Buy an item. The user is prompted to enter the name of the item they want to buy. If the item is found in the inventory, its price is displayed as a confirmation.

Option 2: Add an item. The user is prompted to enter the details of a new item (name, price, and quantity), which is then added to the inventory vector.

Option 3: Update item details. The user is prompted to enter the name of the item they want to update. If the item is found in the inventory, they can input new price and quantity values.

Option 4: Display items. The details of all items in the inventory vector are displayed using the displayDetails() method of each Product object.

Option 5: Exit the program. The loop is exited, and the program terminates.

If the user selects an invalid option, they receive an error message.

After each operation, the program loops back to the menu and allows the user to perform more actions.

The program continues to run until the user selects option 5 to exit.
