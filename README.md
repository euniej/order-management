# [Order Management and Invoicing System for a Store ]

[Introduction]
This Web Application is designed to provide customers with a seamless shopping experience while facilitating efficient order data management. This application uses MongoDB as the backend database to allow users to browse available products, make purchases, and view order details/history.

[Core Functionality]

1. HTML/CSS: Web Form
   - The web form collects essential information required to process customer orders, including name, shipping address, contact information, and selected products.
   - The form includes options to select at least two products from the available inventory, ensuring flexibility in purchase choices.
   
2. Server-side Programming using JavaScript, EJS, Express, and Node.js
   - Server-side scripting handles the processing of form submissions and generation of receipts.
   - Receipts are dynamically generated to include all customer-entered information and details of the purchased products.


3. Save Data to MongoDB
   - All data submitted through the web form, including customer details and product purchases, is saved to the MongoDB database.
   - Calculated values, if any (such as total order amount), are also stored in the database for future reference.

4. Retrieve Data from MongoDB
   - A dedicated page is implemented to fetch and display order details from the MongoDB database.
   - Order information is presented in a tabular format, providing a comprehensive overview of all customer purchases.

[Skills Required]
- Proficiency in HTML, CSS, and JavaScript for front-end development.
- Knowledge of server-side programming using Node.js, Express, and EJS.
- Experience with MongoDB and Mongoose for database integration.
- Ability to implement CRUD operations for data storage and retrieval.

