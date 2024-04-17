
# MERN-Blog

This is a full-stack web application that allows users to create, read, update, and delete (CRUD) blog posts. It provides a platform for writers and bloggers to share their thoughts and ideas with the world.

# Tech Stack

* Frontend:
   
   * React.js
   * Javascript
   * Axios

* Backend:
 
   * Node.js (Express.js)
   * MongoDB (Mongoose for ODM)
   * JWT for authentication

# Getting Started

 Prerequisites

   * Node.js and npm installed
   * MongoDB server running locally or accessible remotely

   

Installation

   * Fork the repository
   * Clone the repository

```bash
  git clone git@github.com:<your username>/MERN-Blog.git
  cd MERN-Blog

  # Install backend dependencies
  cd server
  npm install

  cd ..
  # Install frontend dependencies
  cd client
  npm install
```

  * Configure environment variables:

    Create a .env file in the backend directory and set:

    ```bash
    MONGO_URL=your_mongodb_connection_string
    JWT_SECRET=your_jwt_secret
    PORT=port
    ```
  * Run the application:
  ```bash
  cd server
  npm run dev

  cd client
  npm run dev
  ```


## API Endpoints: 
 1 - Authentication
 
  * Sign Up: POST /api/users/register
  * Login: POST /api/users/Login

 2 - Pages

  * GET all posts: GET /api/posts
  * GET user post: GET /api/users/:id
  * GET category posts: GET /api/posts/categories/:category
  * GET author: GET /api/users/:id
  * CREATE post: POST /api/posts
  * UPDATE post: PATCH /api/post/:id
  * EDIT user: PATCH /api/users/edit-user
  * DELETE post: DELETE /api/post/:id

## Testing:

to test all api by running frontend or simply use Postman

## Contributing:

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.
