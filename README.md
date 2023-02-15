# Ecommerce web site

# Steps

1. create react app
2. create git repository
3. create the products data(data.js)
4. create the images folder
5. map the products to a jsx expression
6. add routing
   1. npm i react-router-dom
   2. create route for home screen
   3. create router for product screen
7. create nodejs server
   1. run npm init in back folder
   2. update package.json set type : module
   3. add .js to folder 4. npm install express
   4. create server.js to imports 6. require express
   5. create route for return back is ready
   6. move data .js from front to back
   7. create route for api/products
   8. return products
   9. run npm start
8. manage state by reducer hook
   1. define reducer
   2. update fetch data
   3. get state from usereducer
9. add bootstrap UI framework
   1. npm install react-bootstrap bootstrap
   2. update app.js
10. create product and rating component
    1. create rating component
    2. create product component
    3. use rating component in product component
11. create the description product page
    1. create the descrption card component
    2. conditionel rendering to the statue of the product
    3. change the product descption name using react helmet async
12. create loading and message components
    1. create loading component
    2. use spinner component
    3. create message component
    4. create utils.js to define getError function
13. implement add to card
    1. create react context
    2. define reducer
    3. create store provider
    4. implement add to card button click handler
14. create cart screen
    1. create columns
    2. display item list
    3. create action colummn
15. complete cart screen
    1. click handler for inc/des item
    2. click handler for remove item
    3. click handler for check out
16. create signin screen
    1. create signin form
    2. add email and password
    3. add signin button
17. seed sample product
    1. create product model
    2. create user model
    3. create seed route
    4. use routes in server.js
    5. seed sample product
18. seed sample users
    1. create user model
    2. seed sample users
    3. create user routes
19. create user signin backend api
    1. create signin api
    2. npm install jsonwebtoken
    3. define generate token
20. complete signin screen
    1. handle submit screen
    2. save token in store and local storage
    3. show user name inheader
21. create shipping screen
    1. create form inputs
    2. handle save shipping
    3. add checkout wizard bar
