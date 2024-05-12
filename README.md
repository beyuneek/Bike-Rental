# Bike Rental System

The Bike Rental System is an innovative web application designed to make the renting of e-bikes easy and accessible for urban commuters. This platform allows users to register, browse available bikes, rent them, and manage their rentals efficiently using advanced web technologies.

## Table of Contents

- [Technologies Used](#technologies-used)
- [Features](#features)
- [Setup and Installation](#setup-and-installation)
- [Usage](#usage)
- [Testing](#testing)
- [Contributions](#contributions)
- [Future Enhancements](#future-enhancements)
- [License](#license)

## Technologies Used

- **Node.js**: Server-side JavaScript runtime environment.
- **Express.js**: Web application framework for Node.js.
- **MongoDB**: NoSQL database used to store all application data.
- **Mongoose**: ODM (Object Data Modeling) library for MongoDB and Node.js.
- **React.js**: A JavaScript library for building user interfaces.
- **JWT (JSON Web Tokens)**: Used for secure user authentication.
- **bcrypt.js**: Used for hashing and securing user passwords.

## Features

- **User Authentication**: Users can securely register and log in to the system.
- **E-bike Catalog**: After logging in, users can browse through the list of available e-bikes.
- **Rent and Manage Bikes**: Users can rent available bikes and view their rental history.
- **Admin Panel**: Administrators can manage bike inventory and user accounts.
- **Payment Integration**: Integrated payment gateway for processing transactions securely.
- **User Reviews**: Users can leave reviews for the bikes they have rented.
- **Route Planning**: Integrated mapping services allow users to plan their routes.

## Setup and Installation

```bash
# Clone the repository
git clone https://yourrepositorylink.com
cd Bike Rental System

# Install backend dependencies
npm install

# Set up environment variables
echo "DATABASE_URL=your_mongodb_connection_string" >> .env
echo "SECRET_KEY=your_jwt_secret_key" >> .env

# Start the backend server
npm start

# Navigate to the client directory and install dependencies
cd client
npm install

# Start the React application
npm start
