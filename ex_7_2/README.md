# Exercise 7_2

Create REST API for the car database. REST API should have following endpoints.

The root endpoint of the REST API is http://localhost:3000/cars

REST API has following endpoints and actions.

| Method and endpoint | Action |
| --- | --- |
| GET /cars | Fetch all cars |
| POST /cars | Add new car. New car is send inside the request body. |
| POST /api/customers | Add new customer- New customer is send inside the request body. |
| DELETE /cars | Delete car by id. Id is sent in the request body. |
| PUT /cars/{id} | Edit car by id. Id is sent in the route parameter and updated car inside the request body. |