# IMS-Project-ETG-Internship
The project is an inventory management system. I have divided it into four parts.

The first section of the project contains a nested dictionary of 50 products with product id as the key and other details like product name, price, expiry date, quantity, and category as the value of each key. Then the dictionary is converted to a JSON file.

The second part contains code to display only the product id, and the product name is a neat way to the user.

The third part contains the code to prompt the user for the product id against which the product name and price are displayed, then the user is asked to enter the quantity of product he wants to purchase. It goes on in a loop until the user types in done. In each iteration, a confirmation message is displayed for the user. Finally, after the user enters done, the total bill is displayed. The user is asked if he wants to print the bill.  If he types yes, a well-presented bill is given with the product name, discounted price, normal price, category. I formatted it in a table format using f strings. 

Fourth part: Finally, the number of products purchased by the user is modified in the copy of the main dictionary and the sales.json is created which contains the details of the products sold.
