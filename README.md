#Angular Product Management Application

####This Angular application empowers users to manage products, facilitating tasks such as adding new products, modifying existing ones, checking/unchecking product status, and deleting products.

##Product Modification Component Overview
####This component handles the modification of existing products. It retrieves product details based on the productId route parameter and populates the form for modification.

##Component Model (edit-product.component.html)
####This HTML template defines the layout for the product modification component. It includes form fields for product name, price, and a checkbox for status, along with a submit button.

##TypeScript Component Logic (edit-product.component.ts)
####This TypeScript file contains the logic for the product modification component. It retrieves the product details on initialization, populates the form, and handles the submission to update the product.

##New Product Component Overview
####This component is responsible for adding new products. It provides a form for users to input the name, price, and status of the new product, along with a submit button.

##Component Model (new-product.component.html)
####The HTML template defines the structure of the new product component, including form fields for name, price, and a checkbox for status, along with a submit button.

##TypeScript Component Logic (new-product.component.ts)
####This TypeScript file contains the logic for the new product component. It initializes the form and handles the submission to save the new product.

##Product List Component Overview
####This component lists all products, allowing users to search, check/uncheck, delete, and paginate through the products.

##Component Model (products.component.html)
####The HTML template defines the layout for the product list component. It includes a search input field, a table to display product details, buttons for checking/unchecking, deleting, and editing products, and pagination controls.

##TypeScript Component Logic (products.component.ts)
####This TypeScript file contains the logic for the product list component. It handles product search, checking/unchecking, deletion, pagination, and navigation to the edit product page.

##Application State Service Overview
####This service manages the application state, including product data, search keyword, pagination details, and total product count.

##Service Logic (app-state.service.ts)
####This TypeScript file defines the application state service, which initializes the product state and provides methods to update the state.

##Product Management Service Overview
####This service manages CRUD operations for products, including searching, checking/unchecking, deleting, saving, retrieving by ID, and updating products.

##Service Logic (product.service.ts)
####This TypeScript file contains the logic for the product management service, which interacts with the backend API to perform CRUD operations on products.
