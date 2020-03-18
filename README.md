# ecom

API to retrieve product information

Setup:
Clone the project and start it using node index.js

1. List all products
  URL: http://localhost:8000/api/v1/products/
  Method: GET
  
2. Add a product
  URL: http://localhost:8000/api/v1/products/create
  Method: POST
  Request format:
    product: {
    name: laptop,
    quantity: 10
  }
  provide the two fields along with their values in the body in x-www-form-urlencoded format
  
3. Delete a product  
  URL: http://localhost:8000/api/v1/products/:id
  Method: DELETE
  
4. Update a product
  URL: http://localhost:8000/api/v1/products/:id/update_quantity
  Method: POST
  Request format:
    {
    quantity: 10
  }
  provide the quantity value in the body in x-www-form-urlencoded format

