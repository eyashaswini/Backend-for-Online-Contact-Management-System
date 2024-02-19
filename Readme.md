Database Schema
 
User Table
 
1. User_id (Primary Key)
2. Name
3. Phone Number
4. Email
 
Endpoints
 
1. POST /api/v1/users – Add Users
This endpoint allows the addition of users to the system. Use a POST request to add new users, providing details such as name, phone number, and email in the reqest body.
 
2. GET /api/v1/users/{id} – Get User Details
Retrieve detailed information about a specific user by providing the user ID in the request path.
 
3. PUT /api/v1/users/{id} – Update User
Update user information using a PUT request. Provide the updated details in the request body, allowing users to modify their information.
 
4. DELETE /api/v1/users/{id} – Delete User
Effortlessly remove a user from the system using a DELETE request with the user ID in the path