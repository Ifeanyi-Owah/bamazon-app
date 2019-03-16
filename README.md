# bamazon 

This application implements a simple command line based storefront using Node.js and MySQL. There are three interfaces available in this application:  customer, manager, and supervisor.

## Technologies Used
1.	Javascript
2.	nodeJS
3.	MySQL
4. 	npm packages:
    -	mysql
    -	dot-env
    -	inquirer
    -	colors/safe
    -	cli-table

### Customer Interface
The customer interface allows the user to view the current inventory of store items: item IDs, descriptions, department in which the item is located and price. The user is then able to purchase one of the existing items by entering the item ID and the desired quantity. If the selected quantity is currently in stock, the user's order is fulfilled, displaying the total purchase price and updating the store database. 


