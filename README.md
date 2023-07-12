# PW-CRUD-Assignment
Question : User Management Backend with Express and MongoDB


Objective:
Design and develop a user management backend system using Expressjs and MongoDB, allowing users to
create, login account
Requirements:
1. Implement a RESTful API using Expressjs for handling userrelated operation.
2. Utilise MongoDB as the database for storing user information.
3. Include functionality for user registration, User Login.
4. Ensure proper Validation and error handling throughout the application.
5. Develop clear and wellstructured code with appropriate comments.
6. Provide API documentation, including endpoints, request/response formats, and error handling.


## Features

- Create a Middleware that checks if user has provided mandatory field to register as name,email,password if validation failed send resp as {msg:"all input fields are required"}

- Create a Middleware that checks if user  has provided mandatory field to login as email,password if validation failed send resp  as {msg:"all input fields are required"}     

- Check if user acocunt exist with email if not send resp as {msg:"No account associate with this email"} else check password


- Check if user has provided correct password or not  if wrong password send resp as {msg:"Password is wrong"} else {msg:"User login successfully"}   
