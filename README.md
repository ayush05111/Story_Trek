# Story Trek Blog Application
Story Trek is a user-friendly blog application developed using modern technologies like React.js, Node.js, MongoDB, and Express. This application enables users to effortlessly manage blog posts by implementing CRUD (Create, Read, Update, Delete) operations.

Technologies Used
React.js: Frontend development framework used for building the user interface.
Node.js: Backend framework utilized for server-side operations.
Express: Web application framework used in Node.js for routing and middleware.
MongoDB: NoSQL database used for efficient storage and retrieval of blog post data.
Features
CRUD Operations: Allows users to Create, Read, Update, and Delete blog posts easily.
User-Friendly Interface: Developed with a focus on providing a seamless and intuitive user experience.
Efficient Data Storage: Utilizes MongoDB for storing and retrieving blog post data efficiently.

Setup Instructions
To run the Story Trek blog application locally, follow these steps:  

1.Clone the repository:
```
git clone https://github.com/ayush05111/Story_Trek.git
cd story-trek
```
2.Install Dependencies:  
```
# Install backend dependencies
cd server
npm install

# Install frontend dependencies
cd ../client
npm install
```


3.Set Up MongoDB:

Install MongoDB on your local machine or use a cloud-based MongoDB service.
Update the MongoDB connection string in the backend configuration file (server/config/db.js).    

4. Run the Application:  
Start the backend server  
```
cd ../backend
npm start
```
Access the Application:
Open your web browser and visit http://localhost:3000 to access the Story Trek blog application.

Start the frontend server  
```
cd ../client
npm start
```
# Author
Ayush Sharma  

# License
This project is licensed under the MIT License. 
