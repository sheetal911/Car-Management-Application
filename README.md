# Car-Management-Application
The Car Management Application allows users to manage a collection of cars with features for adding, viewing, updating, and deleting car details. It supports image uploads, car searches, and user authentication, providing a seamless experience for car inventory management. The application is hosted on a cloud platform for easy access.
Car Management Application
Objective
The Car Management Application allows users to manage their car listings by performing CRUD (Create, Read, Update, Delete) operations. Each car listing can contain up to 10 images, a title, a description, and relevant tags such as car type, company, and dealer. The application includes user authentication, ensuring users can only manage their own products. A global search functionality allows users to search through their car listings using keywords.

Functionalities
User Authentication:
Users can sign up and log in to access their products.
Car Management:
Users can add a car with up to 10 images, a title, a description, and tags (e.g., car_type, company, dealer).
Users can view a list of all their cars.
Users can click on a car to view its details.
Users can update the title, description, tags, or images of a car.
Users can delete a car.
Search:
Users can search for cars based on the title, description, or tags.
Frontend Pages
Sign Up / Login Page:
Allows users to register and log in.
Product List Page:
Displays a list of all cars created by the logged-in user with an option to search through them.
Product Creation Page:
A form to upload car images, set a title, and write a description for new cars.
Product Detail Page:
Displays the details of a car with options to edit or delete it.
Exposed APIs
POST /api/users/create - Create a new user.
POST /api/products/create - Add a new car product.
GET /api/products - List all products of the logged-in user.
GET /api/products/{id} - Get the details of a particular product.
PUT /api/products/{id} - Update a car product.
DELETE /api/products/{id} - Delete a car product.
GET /api/docs - API documentation (generated using Swagger/Postman).
Tech Stack
Frontend: React.js (or any other frontend framework of choice)
Backend: Node.js with Express.js (or any backend technology)
Database: MongoDB (or any other database)
Authentication: JWT-based token authentication
Cloud Deployment: Heroku or Vercel
How to Run the Application
Clone the repository to your local machine.
Install the required dependencies for both frontend and backend.
For frontend: npm install
For backend: npm install
Set up the database and configure environment variables.
Start the backend server and frontend application.
For backend: npm start
For frontend: npm start
Access the application through http://localhost:3000 (or any other configured port).
API Documentation
The API documentation is available at /api/docs. This documentation includes details about the request parameters, authentication requirements, and response structure.

Deployment
The application is deployed on Vercel. You can access it through the following link:


Conclusion
This application provides a comprehensive solution for managing car listings with easy-to-use features like authentication, image uploads, car details management, and search functionality. The system ensures that users can only manage their own products while also offering an intuitive interface.

