# Technologies Used

React.js
React Router for navigation
Axios for API requests
Tailwind CSS for styling
Context API for state management

# Prerequisites

Node.js (v14 or later)

# Installation

Clone the repository:
git clone https://github.com/Ankit-can-ctrl/userList.git

Install dependencies:
npm install

# Adding Tailwind CSS to Your Project

# Install Tailwind CSS:

write these below two commands inside project directory:

npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p

# Configure your template paths in tailwind.config.js:

Paste this instead of config in tailwind config file :

content: [
"./src/**/*.{js,jsx,ts,tsx}",
],

# Add the Tailwind directives to your CSS in src/index.css:

clear the index.css file and paste these three tailwind lines:

@tailwind base;
@tailwind components;
@tailwind utilities;

# Start the development server:

npm start

Open your browser and navigate to http://localhost:5173

# API Endpoints

This app uses the following Reqres API endpoints:

POST /api/login - Authentication
GET /api/users?page=1 - Retrieve users with pagination
GET /api/users/{id} - Get a single user
PUT /api/users/{id} - Update user
DELETE /api/users/{id} - Delete user

# Usage

Login Credentials (for testing)

Email: eve.holt@reqres.in
Password: cityslicka
