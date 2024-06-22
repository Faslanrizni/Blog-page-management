# Blog Management System - MERN Stack

This project is a Blog Management System developed using the MERN stack (MongoDB, Express.js, React.js, Node.js). The application features user registration, login, blog post management, and access to protected resources.

## Features

### User Registration
- Users can register for the platform by providing a unique username, email address, and password.
- The backend API validates the input, ensuring the username and email are unique, and the password meets security criteria.
- User data, including username, email (encrypted password), and profile information, is securely stored in a database.

### User Login
- Registered users can log in by entering their username or email and password.
- The backend API verifies the credentials against the stored data, checking if the password is correct.
- If the credentials are valid, the API generates an access token and returns it to the front end.

### Blog Post Management
- Authenticated users can create, edit, and delete their blog posts.
- The backend API handles requests to create new blog posts, update existing ones, and delete posts if needed.
- Each blog post includes a title, content, publication date, and author information.

### Protected Resources
- Authenticated users can view and manage their own blog posts on their dashboard.
- The backend validates the access token before allowing access to the user's blog posts.

## Project Structure

### Backend (API)
The backend of this Blog Management System is built using Node.js, Express.js, and MongoDB. The API handles user authentication, blog post management, and access to protected resources.

GitHub Repository: [Backend API](https://github.com/Faslanrizni/blog-page)

### Frontend (Client)
The front end of the Blog Management System is built using React.js. It interacts with the backend API to provide a seamless user experience for managing blog posts and accessing protected resources.

GitHub Repository: [Frontend Client](https://github.com/Faslanrizni/blog-page-client)

## Getting Started

### Prerequisites
- Node.js
- MongoDB
- npm or yarn

