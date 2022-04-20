# MERN E-STORE

#STEPS

1. Install Tools (Node, GitBash)
2. Create React APP
3. Create Git Repository
4. List Products
   4.1 creating products array
   4.2 add product images
   4.3 render products
   4.4 style products
5. Add Page Routing
   5.1 npm i react-router-dom
   5.2 create route for home screen
   5.3 create router for product screen
6. Create Node.JS Server
   6.1 run npm init in root folder
   6.2 Update package.json set type: module
   6.3 Add .js to imports
   6.4 npm install experess
   6.5 create server.js
   6.6 add start command as node backend/server.js
   6.7 require express
   6.8 create route for / return backend is ready.
   6.9 move products.js from frontend to backend
   6.10 create route for /api/products
   6.11 return products
   6.12 run npm start
7. Fetch Products from backend
   7.1 set proxy in package.json
   7.2 npm install axios
   7.3 use state hook
   7.4 use effect hook
   7.5 use reducer hook
8. Manage State By Reducer Hook
   8.1 define reducer
   8.2 update fetch data
   8.3 get state from useReducer
9. Add Bootstrap UI
   9.1 npm install react-bootstrap bootstrap
   9.2 update App.js
10. Create Product and Rating Component
    10.1 Create Rating Component
    10.2 Create Product Component
    10.3 Use Rating Component in Product Component
11. Create Product Details Screen
    11.1 Fetch Product from Backend
    11.2 Create 3 Columns for image, info and action
12. Create Loading and Message Component
    12.1 Create Loading Component
    12.2 Use Spinner Component
    12.3 Create Message Component
    12.4 Create utils.js to define getError function
13. Implement Add to Cart
    13.1 Create React Context
    13.2 Define Reducer
    13.3 Create Store Provider
    13.4 Implement Add To Cart Button Handler
14. Complete Add To Cart
    14.1 check exist item in the cart
    14.2 check count in stock in backend
15. Create Cart Screen
    15.1 Creat two columns
    15.2 Display Item List
    15.3 Create Action Column
