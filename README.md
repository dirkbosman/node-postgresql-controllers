# node-postgresql-controllers

A (Destructured) Express Node PostgreSQL App w. Controllers

#### Summary:

- node express server, middleware and apis
- postgresql relational database

#### Boilerplates:

- [Part 1: node-postgresql-unstructured](https://github.com/dirkbosman/node-postgresql-unstructured)
- [Part 2: node-postgresql-destructured](https://github.com/dirkbosman/node-postgresql-destructured)
- [Part 3: node-postgresql-controllers](https://github.com/dirkbosman/node-postgresql-controllers)

#### To Do's:

1. If you haven't done it yet, create _POST_ _PUT_ and _DELETE_ routes for orders
2. Move the business logic of the orders in the `controllers/orders.js` as it's been done for users.
3. (OPTIONAL) Look into [sequelize](https://sequelize.org/master/), an ORM for SQL

#### Curl Requests:

```
curl -d '{"name": "Jiggly", "surname": "Puff", "age": 100}' -H "Content-Type: application/json" -X POST http://localhost:3000/users
curl -d '{"name": "Jiggly", "surname": "Puff", "age": 3}' -H "Content-Type: application/json" -X PUT http://localhost:3000/users/2
curl -d '{"price": 10, "user": 2}' -H "Content-Type: application/json" -X POST http://localhost:3000/orders
curl -d '{"price": 12, "user": 5}' -H "Content-Type: application/json" -X PUT http://localhost:3000/orders/5
```
