# IMS-Project-ETG-Internship
The project is a inventory management system. I have divided it in four parts.

The First part contains a nested dictionary of 50 products with product id as the key and other details like product name, price, expiry date, quantity and category as value of each key.Then the dictionary is converted to json file.

The Second part contain code to display only the product id and the product name is a neat way to the user.

Third Part involves the code to prompt the for the product id against which the product name and price is displayed, then user is asked to enter the quantity of product he wants to purchase. It goes on in a loop untill user types in done. In each iteration, confirmation message is displayed to the user. Finally after user enters done, total bill is displayed. User is asked if he wants to print a bill.  If he types in yes, a well presented bill is displayed with the product name, discounted price, normal price, category. I formated it in a table format using f strings. 

Fourth Part: whatever user purchases is modified in the copy of main dictionary and the sales.json is created.
