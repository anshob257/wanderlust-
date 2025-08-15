Wanderlust - Airbnb Clone Project🔥
Welcome to Wanderlust, a feature-rich web application inspired by Airbnb, designed to help users discover, book, and manage travel accommodations with ease. This project includes user authentication, map integration for location-based browsing, and a seamless booking system. Follow the steps below to set up and run Wanderlust on your local machine.
Features

User Authentication: Secure login and registration system for personalized user experiences.
Map Integration: Interactive maps to explore listings by location.
Booking System: Easy-to-use interface for booking accommodations.
Cloudinary Integration: Upload and manage images for listings.
Responsive Design: Optimized for both desktop and mobile devices.

Prerequisites
Before you begin, ensure the following are installed on your system:

Node.js: Version 18 or higher (LTS recommended).
MongoDB: Either a local MongoDB instance or a MongoDB Atlas account.
Nodemon: Install globally using npm install -g nodemon for automatic server restarts during development.

Installation Steps
1. Clone the Repository
Clone the Wanderlust repository from your preferred Git hosting service and navigate to the project directory:
git clone git remote add origin https://github.com/anshob257/wanderlust-.git
cd Wanderlust

2. Set Up Environment Variables
Create a .env file in the root directory and add the following configurations:
# MongoDB connection string (use local MongoDB or Atlas URL)
MONGODB_URI=mongodb://localhost:27017/wanderlust

# Application secret for session management
APP_SECRET=your_secure_application_secret


MongoDB: Replace MONGODB_URI with your MongoDB Atlas connection string or keep the local default if using a local MongoDB instance.
APP_SECRET: Use a strong, unique string for securing sessions.

3. Install Dependencies
Install the required Node.js packages by running:
npm install

4. Start the Development Server
Launch the application using Nodemon to enable live reloading:
nodemon server.js

If Nodemon is unavailable, you can start the server with:
node server.js

5. Access the Application
Once the server is running, open your browser and navigate to:
http://localhost:3000

6. Explore the Application

Register/Login: Create an account or log in to access personalized features.
Browse Listings: Use the map to explore accommodations.
Book a Stay: Select a listing and complete the booking process.

Troubleshooting

MongoDB Issues: Ensure your MongoDB service (mongod) is running or verify your MongoDB Atlas connection string.
Environment Variables: Double-check .env file values for accuracy, especially Cloudinary and MongoDB configurations.
Port Conflicts: If localhost:3000 is unavailable, check for other running services or change the port in server.js.
Nodemon Not Found: Run npm install -g nodemon or use node server.js as a fallback.

License
This project is licensed under the MIT License. See the LICENSE file for details.
Acknowledgments
Built with passion for travel and technology. Special thanks to the open-source community for tools like Node.js, MongoDB.

Made  by ANSH OBERAI

Happy traveling with Wanderlust! 🌎✨
