# Ecommerce-API

Design an API for an ecommerce platform admin to manage product inventory
- Tech Stack: Node.js &amp; Mongo DB
- Test your API’s using Postman
- Models/Schemas:
- Products [fields: id, name, quantity]
*************************************************************************
- API to add products to the database
URL [POST]: /products/create

- API to list products
URL [GET] : /products

- API to delete products
URL [DELETE] : /products/:id

- API to update quantity of a product (can be incremented or decremented)
URL [POST] :
/products/:id/update_quantity/?number=10
/products/:id/update_quantity/?number=-10
