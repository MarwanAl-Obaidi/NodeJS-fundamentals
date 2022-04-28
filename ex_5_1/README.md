# Exercise 5_1

Create REST API that handle customer data. Use the following customer data in your implementation

```
let customers = [
  {id: '1588323375416', firstName: 'John', lastName: 'Johnson', email: 'john@johnson.com', phone: '8233243'},
  {id: '1588323375417', firstName: 'Mary', lastName: 'Smith', email: 'mary@smith.com', phone: '6654113'},
  {id: '1588323375418', firstName: 'Peter', lastName: 'North', email: 'peter@north.com', phone: '901176'},
]
```

The id is generated using "Date.now()" function.

The root endpoint of the REST API is http://localhost:3000/api/customers

REST API has following endpoints and actions.

| Method and endpoint | Action |
| --- | --- |
| GET /api/customers | Fetch all customers |
| GET /api/customers/{id} | Fetch customer by id. Id is sent in the route parameter |
| POST /api/customers | Add new customer- New customer is send inside the request body. |
| DELETE /api/customers/{id} | Delete customer by id. Id is sent in the route parameter |
| PUT /api/customers/{id} | Edit customer by id. Id is sent in the route parameter and updated customer inside the request body. |