# Welcome to the Express RESTful API! 👋

This backend API is built using Express and deployed in a serverless environment on Render. It effectively handles GET and POST requests for managing records in a MongoDB cluster, including insertion, deletion, and updates.

## Using This API

Feel free to integrate this API into your project! It provides JSON data of home decor products 🏠 for eCommerce apps, featuring categories like:

- Sofa
- Clocks
- Tables
- Bookshelves
- And more!

### Product Properties

Each product includes the following properties:

- **id**
- **name**
- **price**
- **brand**
- **description**
- **image_url**
- **rating**
- **category**

### Accessing the API

The main source file is `index.js`, with all routes handled by `user.js`, accessible via the link `/api/users/...`.

To access the JSON data, use the endpoint:  
`https://ecomm-api-enigmaybyte.onrender.com/api/users/products/`

### Available Categories

The API supports the following categories:

- Sofa
- Table
- Chair
- Bed
- Vase
- Shelf
- Clock
- Statues
- Lights1
- Lights2
- Lights3
- Candle
- Mirror
- Diffuser
- Art
- Oils

For example, to retrieve all vases, simply call:  
`https://ecomm-api-enigmaybyte.onrender.com/api/users/products/vase`

### Example Response

An example response is attached here:  
![Example Response](/response.PNG)

## Feedback

If this API proves useful, consider giving a star ⭐ to this repository! If you encounter any unexpected behavior or issues, please open an issue.
