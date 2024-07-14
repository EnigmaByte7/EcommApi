# Hey there 👋!
This is the backend RESTful api built using express and deployed in a serverless environmet on render.\
The api is capable of handling GET, and POST requests effectively handling the insertion, deletion , updation of the records in my mongoDB cluster.

# Using this api
Feel free to use this api in your project.\
The api provides json data of products (particularly home decor products) 🏠 for Ecommerce apps including categories like sofa, clocks, table, bookshelves... \
each product has following properties :

-id
-name
-price
-brand
-description
-image_url
-rating
-category

index.js is the main source file, all the routes are handled by user.js (projecting the link /api/users/..)\
Use this endpoint `https://ecomm-api-enigmaybyte.onrender.com/api/users/products/` to access the json data ...\
it supports following categories \

-sofa
-table
-chair
-bed
-vase
-shelf
-clock
-statues
-lights1
-lights2
-lights3
-candle
-mirror
-diffuser
-art
-oils

So, if you want to pull the json of all vases, all u need to do is call this endpint ... `https://ecomm-api-enigmaybyte.onrender.com/api/users/products/vase`, and thats it.\
 A result example is attached here 	(/response.PNG)\
 
 ## If this api proves useful for you consider giving a star ⭐ to this repo 😸
 ## Or if you find any unexpected behavior or any mistakes please open a issue
