# Business_Dealings

Developed a website during my 3rd year created using Node Js, Mongo database, HTML, CSS and JavaScript.

This website consists of ordering of goods [ Client Side ] and selling of goods [ Admin Side ].

# Customer Login:
  Order & Acknowledgement
  Quantity Based On Inventory
  Purchase History

# Admin Login:
  Inventory
  Dynamic Pricing Mechanism
  Analysis [Graph]

# Online Product Sales:
  The project has the domain of Web Development. It is a marketing website which has both customer
  and admin.

# Under Customer Login :-
      On logging in the customer’s welcome page, he can view the items for sale along with their cost. He also
      has options like purchase, products and history.
    
      ● Purchase Option: It shows all the purchases made by him of each product along with their total cost.
      
      ● Products Option: On pressing this option, it opens up a new tab, which consists of the products
      available along with their description and another option “To Order” is provided. On pressing “To Order”
      option we are taken to a page which shows the product name, price per product, input box for entering
      the quantity of products required and a submit option. If the Quantity entered is greater than available
      quantity then a message will be shown saying that the “value should be less than the quantity
      available”. If the quantity is less than that of available quantity, then on pressing submit it takes us to a
      Purchase Successful page which shows all details of the purchase made like the product name, Price per
      Unit, Ordered Quantity and Total Price. There is also another option to return to the Products page.
      
      ● History Option: This option shows takes us to a new tab which shows us the option to choose a certain
      product. On choosing the product, A table is shown which has the serial number, date & time of the
      purchase, Price per unit, Ordered quantity at that date and time and total Price.

# Under Admin. Login :-

      On logging in the admin’s welcome page, he can view the items along with the name, price
      and available quantity. There are options available for him to choose which include
      
      Inventory for update and analysis.
      
      ● Inventory Option: It shows a tabular column which has the product’s name, price of the product, total
      quantity of the product, Sold quantity of the product and available quantity.
      
      ● To Update Option: It takes us to a new tab where we have to choose the product to update, On
      choosing the product, there is a tabular column which consists of current price of the product, an input
      tab for updating the price of the product and suggested price update. The dynamic pricing update
      works by checking if the sold quantity is greater than half of total quantity and if sold quantity is less
      than total quantity – 30 then 5% increase of the current price will be shown. But if sold quantity is equal
      to total quantity or sold quantity is greater than total quantity minus 30 then 15% increase of the
      current price will be shown. But if none of the above conditions match and sold quantity is less than 50%
      of total quantity then current price will be shown as it is. The next row shows the current quantity of the
      product, an input tab for adding to the current quantity.
      
      ● Analysis Option: It takes us to another page which shows a bar chart of the sold quantity in red colour
      and available quantity in blue colour along with the product name in X-Axis and product quantity in Y
