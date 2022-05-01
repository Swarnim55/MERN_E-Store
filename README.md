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
16. Complete Cart Screen
    16.1 Implement Click Handler for inc/dec item
    16.2 Implement Click Handler for remove item
    16.3 Implement Click Handler for checkout
17. Create Signin Screen
    17.1 Create Signin Form
    17.2 Add Email & Password
    17.3 Add Signin Button
18. Connecting to MongoDB
    18.1 Creating on MongoDb Atlas (cloud) DB
    18.2 Installing Local MongoDb Database
    18.3 npm install mongoose
    18.4 Connecting to mongodb database
19. Seed Sample Data
    19.1 Create Product Model
    19.2 Create User Model
    19.3 Create Seed Route
    19.4 Use Route in server.js
    19.5 Seed Sample Product
20. Seed Sample Users
    20.1 Create User Model
    20.2 Seed Sample Users
    20.3 Create user routes
21. Create Signin Backend API
    21.1 create signin api
    21.2 npm install jsonwebtoken
    21.3 define generateToken
22. Complete Signin Screen
    22.1 Handle submit action
    22.2 save token in store and local storage
    22.3 show username in header
23. Create Shipping Screen
    23.1 create form inputs
    23.2 handle save shipping address
    23.3 add checkout wizard bar
24. Create Signup Screen
    24.1 create input forms
    24.2 handle submit
    24.3 create backend api
25. Implement Select Payment Method Screen
    25.1 create input forms
    25.2 handle submit
26. Create Place Order Screen
    26.1 show cart items, payment and address
    26.2 handle place order action
    26.3 create order create api
27. Implement Place Order Action
    27.1 Handle Place order Action
    27.2 Create Order Create Api
28. Create Order Screen
    28.1 Create backend api for order/:id
    28.2 Fetch Order API in frontend
    28.3 Show Order Information in 2 columns
29. Pay Order By Paypal
    29.1 Generate Paypal Client ID
    29.2 create api to return client ID
    29.3 install @paypal/react-paypal-js
    29.4 use PaypalScriptProvider in index.js
    29.5 use usePaypalScriptReducer in Order Screen
    29.6 implement loadPaypalScript function
    29.7 render paypal button at checkout
    29.8 implement onApprove payment function
    29.9 create pay order api in backend
30. Display Order History
    30.1 create order screen
    30.2 create order history api
    30.2 use api in frontend
