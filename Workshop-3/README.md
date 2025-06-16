
Editor.md
Open source online Markdown editor.

# Workshop-3
####How to review or run the update designs.
#####1. UML Diagram
how to review?
This diagram represents the main structures of the system, showing:
- The classes: Register, Profile, Customer, Seller, APP, Product, Offer, Payment. 
- Their attributes and methods . 
- The relationships: inheritance (extends), composition ,agregation , and direct association.
​
#####2.  Activity Diagram: Product Purchase  
How is it executed?
1. The user chooses to register → their data is taken and they are registered. 
2. Then they log in → enter data → access.
3. In the main interface, offers are shown → if accepted, they enter the main interface; if not, they view categories. 
4. They choose a product → add it to the cart/purchases. 
5. They make the payment → payment methods are displayed, data is entered, and 'pay' is pressed.
6. Finally, the status of the package can be checked and they can return to the home.
​
​
#####3. Activity Diagram: Add Product
How is it executed?
1. The user (seller) registers and then logs in.
2. From the main interface, they press 'add product'.
3. The data for the new product is taken and published.
4. Finally, the published product is displayed.
​
#####4. Sequence Diagram: Customer Flow
How is it executed?
1. The customer registers, the profile is saved.
2. Then they log in → data verification.
3. The product is shown and selected.
4. They press "buy now".
5. Product data is exchanged.
6. Payment is selected → data and package status are sent.
​
#####5. Sequence Diagram: Seller Flow
How is it executed?
1. The seller registers and a profile is created.
2. Then they log in → it is validated.
3. They request to see sales → the system responds with the sold products.
  
