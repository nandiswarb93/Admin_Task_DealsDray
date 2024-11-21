MERN Stack Admin Panel Task This project is an admin panel built using the MERN (MongoDB, Express.js, React.js, Node.js) stack. The admin panel provides a simple interface for managing and interacting with the backend.

Project Setup To get started, follow these steps:

Clone the Repository First, create a folder on your local machine and initialize it with Git.
bash Copy code mkdir your-folder cd your-folder git init git clone https://github.com/nandiswarb93/Admin_Task_DealsDray.git
[2. Install Dependencies Backend Setup: 
#####################

Navigate to the backend folder in one terminal and install the required dependencies.]

###############
cd backend npm install express jsonwebtoken multer cloudinary dotenv mongoose mongodb Client Setup: In another terminal, navigate to the client folder and install the frontend dependencies.

######################
cd client npm install axios react-router-dom 3. Environment Variables Create a .env file in the backend directory and provide the necessary environment variables (e.g., database connection string, API keys for Cloudinary, etc.).
#
Example .env file:
########################################
makefile 
#   MONGO_URI=your_mongo_database_uri
#   JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
4. Running the Project To run the project, you need to open two separate terminal windows:

In the first terminal, navigate to the client folder and start the frontend:
cd client npm start 

############################################
In the second terminal, navigate to the backend folder and start the backend::

 cd backend npm start Your application will be running at http://localhost:3000.

Access the Project After setting up the backend and frontend, you should be able to access the admin panel in your browser at http://localhost:3000.
