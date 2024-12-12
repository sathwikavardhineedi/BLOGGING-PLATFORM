
A full-stack blogging platform built with the MERN stack (MongoDB, Express.js, React.js, Node.js). This application allows users to create, edit, and manage blogs with a user-friendly interface and robust backend features.

## Features

- User Authentication: Secure login and signup functionality.
- Blog Management: Create, edit, delete, and view blogs.
- Responsive UI: A clean and responsive design for seamless user experience across devices.
- Scalable Architecture: Built with modular components and a robust backend.

## Tech Stack

- Frontend: React.js, styled with modern CSS libraries.
- Backend: Node.js with Express.js.
- Database: MongoDB for data persistence.
- Authentication: JSON Web Tokens (JWT).

## Installation and Setup

Follow the steps below to set up the project locally:

### Prerequisites
Ensure you have the following installed:
- Node.js
- MongoDB
- npm or yarn package manager

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/sathwikavardhineedi/BLOGGING-PLATFORM
   cd mern-blog
   ```

2. Install dependencies for the server:
   ```bash
   cd server
   npm install
   ```

3. Install dependencies for the client:
   ```bash
   cd ../client
   npm install
   ```

4. Set up environment variables:
   - Create a `.env` file in the `server` directory with the following variables:
     ```
     MONGO_URI=your_mongodb_connection_string
     JWT_SECRET=your_jwt_secret_key
     ```
   - Replace `your_mongodb_connection_string` and `your_jwt_secret_key` with your credentials.

5. Start the application:
   - In one terminal, run the backend:
     ```bash
     cd server
     npm start
     ```
   - In another terminal, run the frontend:
     ```bash
     cd client
     npm start
     ```

6. Open [http://localhost:3000](http://localhost:3000) in your browser to access the application.

## Usage

1. Sign Up / Log In:
   - Create an account or log in using your credentials.
   
2. Create a Blog:
   - Navigate to the "Create Blog" section and start writing your blog posts.

3. Manage Blogs:
   - Edit or delete your blogs as needed.

4. Explore Blogs:
   - View and interact with blogs created by other users.
