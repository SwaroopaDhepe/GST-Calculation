#Item Sorting with GST Calculation
Overview: 
This C program allows users to enter details of multiple items, sorts them by price (from highest to lowest), and calculates the final price after applying a 5% GST (Goods and Services Tax). The program utilizes structured data to store item information and provides a sorted list of items based on price.

Features: 
Accepts item details: Name, Department, and Price.
Calculates the final price after applying a 5% GST.
Sorts items by price from highest to lowest.
Displays the sorted list in a tabular format.

Functions Used: 
1. swap(struct Item *a, struct Item *b)- 
Swaps two Item structures to facilitate sorting.
2. sortItemsByPrice(struct Item items[], int n)- 
Sorts the array of Item structures in descending order based on price using the Bubble Sort algorithm.
3. main()- 
Takes user input for the number of items.
Collects details for each item (Name, Department, and Price).
Computes the final price including GST.
Sorts items based on price.
Displays the sorted list.

Thank you for using this convenience store GST calculation system.
