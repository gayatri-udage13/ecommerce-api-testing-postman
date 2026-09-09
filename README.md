# E-Commerce API Testing using Postman

## Overview
This is a mini e-commerce API testing project developed using Postman.
The project tests different REST APIs such as authentication, products,
and cart operations.

## Technologies
- Postman
- REST API
- JSON
- JavaScript
- DummyJSON

## APIs Tested
1. User Login
2. Get Products
3. Get Product by ID
4. Add Product to Cart
5. Get Cart

## Testing
- Status code validation
- Response body validation
- Authentication testing
- Environment variables
- Automated test scripts

## Example Test
```javascript
pm.test("Status code is 200", function () {
    pm.response.to.have.status(200);
});
