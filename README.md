# Anubis_FOOD_PILE
Updated version of food pile 

1)      First the user will login and after entering the user name and password correctly it will lead the user to the 
      pos form through which he can serch the product by the 'product name' and by the 'product code'.
        User can also see the product details (sorted in ascending order in price) by clicking in the "product details sorted via price" 
      button (this button will sort the products in ascending order of price) after clicking the button in the 
      table (below the button) product details will be shown.
            Helpful .java file is pos.java in this case.

2)      After seeing the product details User can also add the item in to the cart and can remove the item from the 
      cart similiar to 'amazon'. User can also buy the products (whatever he likes) and pay the money.
             Helpful .java file is pos.java in this case.
      
3)      User can not modify the product details. So the database is completely protected from the user.

4)      Only admin (here admin is "Navneet") can add items in the database by using product form. Admin can add new brands 
      edit any brand and can delete any brand using three buttons add, edit and delete in brand form.
             Helpful .java file is product.java and brand.java in this case.
      
5)      For adding new products admin use product form and fill the required information (like product name, price, quantity, 
      barcode and it's status (active or deactive)) and click add button. 
      Admin can also edit and delete the items using edit and delete button.
            Helpful .java file is product.java in this case.
      
6)      Admin can also see the products sorted in ascending order of the price and ascending order of the quantity by clicking 
      the "sorted via price" and "sorted via qty" buttons.
            Helpful .java file is sorting.java in this case.
      
7)      Users can be added via admin by using cashier form.
      Admin can also edit the user details and can delete the user details.
            Helpful .java file is cashier.java in this case.
