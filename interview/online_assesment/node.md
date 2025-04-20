Express.js and React Interview Questions
Express.js Long-Answer Questions

Explain how Express.js simplifies building REST APIs compared to vanilla Node.js. Describe the role of middleware in this process.
What is the purpose of express.json() middleware, and how does it enable parsing of request bodies in Express?
Describe the differences between req.params, req.query, and req.body in Express. Provide a use case for each.
How would you design a RESTful API for a resource like 'users'? Explain the HTTP methods and endpoints you would use.
What are HTTP status codes, and why are they important in a REST API? Provide examples for 200, 201, 404, and 204 in the context of user management.
Explain the difference between a PUT and a PATCH request in a REST API. When would you use each for updating a user resource?
How does JSON Web Token (JWT) authentication work in an Express API? Describe the process of generating and verifying a token.
What is the role of the next() function in Express middleware? Provide an example of a custom middleware that uses next().
Describe how role-based authorization can be implemented in an Express API. What information would you store in a JWT to support this?
What are the benefits of using express.Router() to modularize routes? Explain how you would structure a project with separate route files.
How would you implement pagination in a GET endpoint? Describe the query parameters and logic involved.
Explain how query-based filtering and sorting work in an Express API. Provide an example of filtering users by role and sorting by name.
What is rate limiting, and why is it important for an Express API? Describe how you would implement it without external libraries.
How does bcrypt ensure secure password hashing? Explain the steps involved in hashing and verifying a password in a registration flow.
What is input validation in an Express API, and why is it critical? Name two libraries or techniques for validating request data.
Describe the structure and purpose of an error-handling middleware in Express. How does it differ from regular middleware?
Explain the concept of a RESTful CRUD API for a 'products' resource. List the endpoints, HTTP methods, and their purposes.
How would you secure an Express API against common vulnerabilities like SQL injection, XSS, and CSRF?
What are environment variables, and how do you use them in an Express application to store sensitive data like JWT secrets?
Describe the process of protecting a route with JWT authentication middleware. What happens if the token is invalid or missing?
How would you refactor an Express application to improve modularity and maintainability? Discuss the role of controllers and routers.
Explain the challenges of handling asynchronous code in Express routes. How do you ensure errors in async functions are caught properly?
What are the trade-offs of using an in-memory array versus a database for storing users in an Express API?
How would you scale an Express API to handle high traffic? Discuss strategies like load balancing, caching, and clustering.
Describe best practices for documenting an Express REST API. What tools or formats (e.g., Swagger, OpenAPI) would you use?

Express.js Coding Questions

Write an Express server with a GET / route that responds with 'Server is running'. Include express.json() middleware.
Create a GET /users endpoint that returns a hardcoded array of user objects, each with id, name, and email fields.
Implement a POST /users endpoint that adds a new user to an in-memory array. Parse the request body and return the created user with a 201 status.
Write a GET /users/:id endpoint that returns a user by ID from an in-memory array. Return a 404 status if the user is not found.
Create a PUT /users/:id endpoint that fully updates a user object in an in-memory array. Return 404 if the user doesn't exist and 200 on success.
Implement a PATCH /users/:id endpoint that partially updates a user's fields (e.g., name or email) in an in-memory array. Return 404 if the user is not found.
Write a DELETE /users/:id endpoint that removes a user from an in-memory array. Return a 204 status on success or 404 if the user doesn't exist.
Create a POST /login endpoint that generates a JWT for valid credentials (e.g., hardcoded username: admin, password: secret). Use an environment variable for the JWT secret.
Write a middleware function that verifies a JWT from the Authorization header and protects a GET /protected route. Return 401 if the token is invalid.
Implement a role-based authorization middleware that restricts a GET /admin route to users with an admin role in their JWT. Return 403 if unauthorized.
Create a full CRUD API for a products resource with endpoints: GET /products, POST /products, PUT /products/:id, and DELETE /products/:id. Use an in-memory array.
Refactor the user routes (GET /users, POST /users) into a separate userRoutes.js file using express.Router(). Import and use it in the main app.
Add pagination to a GET /users endpoint that supports page and limit query parameters (e.g., /users?page=2&limit=10). Return paginated results from an in-memory array.
Implement a GET /users endpoint that supports filtering by role (e.g., /users?role=admin) and sorting by name (e.g., /users?sortBy=name).
Write a custom rate-limiting middleware that limits each IP to 100 requests per hour. Store request counts in an in-memory object.
Create a POST /register endpoint that validates name, email, and password (min 6 characters), hashes the password with bcrypt, and stores the user in an in-memory array.
Implement an error-handling middleware that catches all errors in an Express app and returns a JSON response with a status code and message.
Write a GET /products/:id endpoint that retrieves a product by ID from an in-memory array. Return 404 if the product is not found.
Create a POST /products endpoint that adds a new product to an in-memory array. Validate that name and price are present in the request body.
Implement a middleware that logs the HTTP method, URL, and timestamp for every request in an Express app.
Write a PATCH /products/:id endpoint that partially updates a product's fields (e.g., name or price) in an in-memory array. Return 404 if the product is not found.
Create a POST /users endpoint that checks for duplicate emails in an in-memory array before adding a new user. Return a 400 status if the email exists.
Implement a GET /users endpoint that supports searching by name (e.g., /users?name=john) using case-insensitive partial matching.
Write a middleware that validates the presence of required fields (name, email) in a POST /users request body. Return 400 if validation fails.
Create a DELETE /products/:id endpoint that removes a product from an in-memory array. Return 204 on success or 404 if the product doesn't exist.

