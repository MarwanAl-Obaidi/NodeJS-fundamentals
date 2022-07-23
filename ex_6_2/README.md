# Exercise 6_2

Create REST API for the customer database. REST API should have following endpoints.

The root endpoint of the REST API is http://localhost:3000/api/customers

REST API has following endpoints and actions.

| Method and endpoint | Action |
| --- | --- |
| GET /api/customers | Fetch all customers |
| GET /api/customers/{id} | Fetch customer by id. Id is sent in the route parameter |
| POST /api/customers | Add new customer- New customer is send inside the request body. |
| DELETE /api/customers/{id} | Delete customer by id. Id is sent in the route parameter |
| PUT /api/customers/{id} | Edit customer by id. Id is sent in the route parameter and updated customer inside the request body. |