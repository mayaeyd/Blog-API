
Blog API with Node.js and Express
This project is a RESTful Blog API that allows users to view, edit, delete, and post blogs. It was built using Node.js, Express, and bodyParser, adhering to RESTful principles with the use of GET, POST, PATCH, and DELETE HTTP methods.

The API is designed to be flexible and scalable, supporting full CRUD (Create, Read, Update, Delete) operations. It's integrated with a frontend application running on a different port, enabling seamless interaction between the client and server.

The application you can send API requests from is the server.js file, you can run it on port 3000.
The API is built in the index.js file, you can run it on port 4000.

Features:
-View Blogs: Fetch all blog posts or a single post by ID.
-Create Blog: Post new blogs with a simple HTTP POST request.
-Edit Blog: Update existing blogs using the PATCH method.
-Delete Blog: Remove blogs from the database with a DELETE request.

Technologies Used:
-Node.js: For the server-side JavaScript runtime environment.
-Express: As the web application framework for handling API routes.
-bodyParser: Middleware for parsing incoming request bodies.

How to run the application:
1- 
