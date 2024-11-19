# Social Media App (MERN Stack)

A social media platform built using the **MERN stack** (MongoDB, Express, React, Node.js) with **HTML**, **CSS**, and **JavaScript**. The app allows users to create profiles, post updates, follow friends, and engage with content in real-time.

## Features

- **User Authentication:** Secure login and registration.
- **Profile Management:** Users can create and update their profile.
- **Post Updates:** Share text, images, and links with friends.
- **Real-time Updates:** Live feed of posts from users' friends and followers.
- **Follow/Unfollow:** Connect with friends and follow other users.
- **Like/Comment:** Interact with posts through likes and comments.
- **Responsive Design:** Optimized for desktop and mobile devices.

## Tech Stack

- **Frontend:** React, HTML, CSS, JavaScript
- **Backend:** Node.js, Express
- **Database:** MongoDB
- **Authentication:** JWT (JSON Web Tokens)
- **Real-time:** Socket.io (for real-time updates)

## Installation

### Prerequisites

- [Node.js](https://nodejs.org/) (v14 or higher)
- [MongoDB](https://www.mongodb.com/) (for local development or use [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) for cloud database)

### Steps to Run the App Locally

1. **Clone the repository:**
   ```bash
   git clone 
   cd social-media-app
   ```

2. **Install dependencies for both frontend and backend:**

   - Install backend dependencies:
     ```bash
     cd backend
     npm install
     ```

   - Install frontend dependencies:
     ```bash
     cd ../frontend
     npm install
     ```

3. **Set up MongoDB:**

   - If using a local MongoDB instance, make sure it is running.
   - If using MongoDB Atlas, create a cluster and set up the connection string in your `.env` file under `MONGODB_URI`.

4. **Create a `.env` file in the root directory for sensitive configurations:**
   ```plaintext
   MONGODB_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   ```

5. **Start the Backend:**
   ```bash
   cd backend
   npm start
   ```

6. **Start the Frontend:**
   ```bash
   cd ../frontend
   npm start
   ```

7. **Open the app in your browser:**
   Visit `http://localhost:3000` to see your social media app running.

## Usage

- Register for an account to create your profile.
- Log in to access your feed, post updates, and follow other users.
- Interact with posts through likes and comments.

## Contributing

Contributions are welcome! Please fork this repository and submit a pull request for bug fixes or feature enhancements.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
