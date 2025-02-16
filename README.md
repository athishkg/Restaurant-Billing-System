# Restaurant Billing System

This is a simple restaurant billing system built using Python and Tkinter. It allows users to select items from a menu, calculate the total bill, and generate a receipt.

## Features

*   **Graphical User Interface (GUI):**  User-friendly interface for easy interaction.
*   **Menu Selection:**  Displays a list of food and drink items with checkboxes for selection.
*   **Quantity Input:**  Allows users to specify the quantity of each item ordered.
*   **Automatic Calculation:**  Calculates the subtotal, tax, service charge, and total cost.
*   **Receipt Generation:**  Generates a detailed receipt with item quantities, prices, and total amount due.
*   **Reset Functionality:** Clears the current order and resets all values.
*   **Exit Option:**  Provides a confirmation dialog before exiting the application.

## Prerequisites

*   Python 3.x
*   Tkinter (usually included with Python)


2.  **Interact with the GUI:**

    *   Select items from the menu by checking the corresponding checkboxes.
    *   Enter the desired quantity for each selected item in the adjacent entry fields.
    *   Click the "Total" button to calculate the bill.
    *   Click the "Receipt" button to generate a receipt.
    *   Click the "Reset" button to clear the current order.
    *   Click the "Exit" button to close the application.

## Code Structure

*   `your_script_name.py`: Contains the main Python code for the billing system.
    *   Includes Tkinter GUI elements, functions for calculations, receipt generation, and reset functionality.

## Customization

*   **Menu Items and Prices:** Modify the `Drinks_Function` and `Food_Function` frames and associated variables to update the menu items and their prices.
*   **Tax Rate:** Adjust the tax rate within the `TotalofUnit()` function.
*   **Service Charge:**  Modify the service charge within the `TotalofUnit()` function.
*   **GUI Appearance:** Customize the colors, fonts, and layout of the GUI elements within the Tkinter code.
