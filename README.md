#SolJour: Your Ultimate Vacation Rental Platform

#SolJour is a full-stack web application for Home Rental services. It allows users to discover, book, and host unique accommodations around the world. Whether you’re planning a relaxing getaway or looking to earn extra income by hosting guests, Wander Lodge has you covered.


#Features
User Authentication:
Users can register and log in securely using JWT (JSON Web Tokens).
Passwords are hashed and stored securely in the database.
Property Listings:
Browse a wide range of houses, villas, and unique accommodations.
Filter listings by location, amenities, price, and availability.
Booking System:
Users can book properties for specific dates.
Booking history and upcoming reservations are easily accessible.
Host Management:
Hosts can add their own properties to the platform.
Manage property details, availability, and pricing.
Responsive Design:
Material UI components ensure a consistent and user-friendly experience across devices.

#Tech Stack
Frontend:
React.js with Redux for state management.
Material UI for styling and responsive design.
Backend:
Node.js and Express.js for server-side logic.
MongoDB for data storage (houses, users, bookings).
Mongoose as the ODM (Object-Document Mapper).


#Key Features:
Sign up & Log in with Auth, JWT, Bcrypt
Create new Listing with details information
Select & Unselect options
Upload, delete, drag & drop photos
Create Booking with Calendar
Fetch Property Feed by Category
Search any Properties by Keyword
Add & Remove Wishlist item(s)
Upload photos from local & Store in MongoDB
Mongoose Schema
Redux state management
Sass (scss) and Material UI
Getting Started
Clone the Repository:

   git clone    https://github.com/rohitkumsr1209/SolJour.git
Install Dependencies:

   npm install
Run the Development Server:

   npm run dev
Set Up Environment Variables:
Modify the .env file in the root directory in server Folder Add your MongoDB connection string, JWT secret, and other necessary variables.

Visit the App:
Open your browser and navigate to http://localhost:3000. Contributions are welcome! If you find any issues or have ideas for improvements, feel free to submit a pull request.
