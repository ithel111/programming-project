   # programming-project
   # Inventory Management System

This project is a simple **Inventory Management System** written in C. It provides an easy-to-use command-line interface for managing an inventory of items, including adding, updating, displaying, and deleting items.

## Features

- **Add Items**: Add new items with a name, quantity, and price.
- **Display Inventory**: View all items in the inventory along with their details.
- **Update Quantity**: Modify the quantity of an existing item.
- **Delete Items**: Remove an item from the inventory.
- **File Persistence**: Save the inventory to a file (`inventory.txt`) and reload it on program startup.

## File Structure

- `structureddd`: The main source file containing the implementation of the inventory management system.

## How It Works

1. **Loading Inventory**: At the start, the program attempts to load the inventory from a file (`inventory.txt`).
2. **Menu**: The user is presented with a menu to:
   - Add items.
   - Display the inventory.
   - Update the quantity of an item.
   - Delete an item.
   - Save the inventory and exit.
3. **Saving Inventory**: On exiting, the inventory is saved to a file for future use.

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/ithel111/programming-project.git
   # programming-project
