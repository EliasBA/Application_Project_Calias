# Application Calias


Create a minimal Point of Sale (POS) system using the Flask Soft UI Dashboard ([https://github.com/app-generator/flask-soft-ui-dashboard](https://github.com/app-generator/flask-soft-ui-dashboard)) as a base project or **a similar looking Theme**.
 The system should have two pages: a product management page and a checkout page.

**Product Management Page:**

- Create a database table for products with the following columns: id, name, price, tax, and image.
- Implement a form that allows a user to add a new product to the database. The form should include fields for name, price, tax, and image. Use a modal for this.
- Display a table of all products on the product management page. The table should include columns for id, image, name, price, tax

- Add a database table for discount actions with the following columns: id, name, and percentage.
- Implement a form that allows a user to add a new discount action to the database. The form should include fields for name and percentage. Use a modal for this. Place the button for the modal next to the button for the other form.

**Checkout Page:**

- Implement a page that displays a grid of all available products. The grid should include the product image, name, and price.
- When a user clicks on a product in the grid, the quantity should be added to the list of selected products and the price including taxes should be displayed.
- Add a field for entering a discount code or a discount action on the checkout page. When a valid discount code or discount action is entered, the discount percentage should be applied to the total price.
- In the next picture you can see an example how this page could look.

![image](https://user-images.githubusercontent.com/48678218/221244652-8c71cc7f-0fdf-44a3-a3b8-6a0e4ba75b31.png)
 On the left we see the products and on the right the list of selected products and their amounts and the dicount code and tax and a sum field which changes, if products are added or subtracted.

**Database** :

- Product class with attributes id, name, price, tax, and image.
- DiscountCode class with attributes id, name, and percentage.

You will need to create at least those two classes in your models.py.

**Technical Requirements:**

- Use Flask to implement the backend for the system.
- Use SQLAlchemy to connect to the database.
- Use fetch to make GET and POST requests to the backend.
- Use Bootstrap, HTML, CSS, and JS to implement the frontend for the system.
- Delete or hide any unnecessary views from the UI-Dashboard.
- The login logic does not need to be changed.
- The design choices are up to the applicant but should align with the given rules.
- The code should be well-documented and follow best practices.

**Deliverables** :

- A GitHub repository containing the source code for the system.
- A README file with instructions on how to install and run the system.
- The system should be made accessible with the help of a Docker or Flask-run, and the correct requirements should be provided.

Estimated Time: 5-8 hours

Good luck to all applicants!
