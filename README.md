# react-native-fullstack-app
React Native Full Stack Project (React Native / Node Express JS / MongoDB Database)

## Project Description
This project is a full stack application that integrates a React Native mobile client with a Node.js/Express backend and MongoDB database. It offers user authentication (login and register), as well as functionalities for creating posts, viewing "my posts", and managing a personal profile, all backed by real-time API communication and efficient data management.

## Tech Stack
- Client: React Native, Expo
- Server: Node.js, Express, MongoDB, Mongoose
- Authentication: JSON Web Tokens (JWT)

## Setup Instructions

### Prerequisites
- Node.js installed
- Expo CLI installed globally: `npm install -g expo-cli`
- MongoDB running locally or a connection string to a remote instance

### Environment Variables

#### Server (.env)
Create a `.env` file in the server folder with variables:
- MONGO_URL: MongoDB connection string.
- JWT_SECRET: Secret key for JWT authentication.

#### Client (.env)
Create a `.env` file in the client folder with variable:
- REACT_APP_API_URL: URL of the backend server (e.g., http://localhost:5000)

### Run the Project

#### Server
1. Navigate to the server directory.
2. Install dependencies: `npm install`
3. Start the server: `npm run start` (or your defined server command)

#### Client
1. Navigate to the client directory.
2. Install dependencies: `npm install`
3. Start the Expo project: `npm start`

## Additional Notes
Ensure you have configured all environment variables before running the project. For more detailed instructions, refer to the documentation or comments within the code.
