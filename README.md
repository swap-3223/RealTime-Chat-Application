# Full Stack Chat Application Using MERN stack with Websocket

This is a full-stack chat application built using the MERN stack (MongoDB, Express.js, React.js, Node.js) and WebSocket for real-time communication.

## Features

- **Real-time messaging**: Users can send and receive messages in real-time.
- **User authentication**: Secure user registration and login.
- **Online indicators**: See when users are online.
- **Message attachments**: Send and receive attachments.
- **Auto-scrolling**: Automatically scroll to the latest message.
- **Responsive design**: Mobile and desktop friendly UI.

## Prerequisites

- Node.js
- MongoDB
- Git

## Installation

1. **Clone the repository**

    ```bash
    git clone https://github.com/yourusername/chat-app.git
    cd chat-app
    ```

2. **Install server dependencies**

    ```bash
    cd server
    npm install
    ```

3. **Install client dependencies**

    ```bash
    cd ../client
    npm install
    ```

4. **Set up environment variables**

    Create a `.env` file in the `server` directory with the following content:

    ```env
    PORT=5000
    MONGO_URI=your_mongodb_connection_string
    JWT_SECRET=your_jwt_secret
    ```

## Running the Application

1. **Start the MongoDB server**

    Make sure MongoDB is running on your system.

2. **Start the backend server**

    ```bash
    cd server
    npm start
    ```

3. **Start the frontend server**

    ```bash
    cd ../client
    npm start
    ```

4. **Access the application**

    Open your browser and go to `http://localhost:3000`.

## Project Structure

- **client**: Contains the React frontend.
- **server**: Contains the Express backend.
- **models**: Contains Mongoose models for MongoDB.
- **routes**: Contains Express routes for API endpoints.
- **controllers**: Contains the logic for handling requests.
- **middleware**: Contains middleware functions for authentication and error handling.

## Contributing

1. **Fork the repository**
2. **Create a new branch**

    ```bash
    git checkout -b feature/your-feature-name
    ```

3. **Make your changes**
4. **Commit your changes**

    ```bash
    git commit -m 'Add some feature'
    ```

5. **Push to the branch**

    ```bash
    git push origin feature/your-feature-name
    ```

6. **Open a pull request**

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any questions or suggestions, feel free to reach out:

- Email: prafullshimpi2829@gmail.com
- LinkedIn: [Prafull Shimpi](https://www.linkedin.com/in/prafull-shimpi-475571228/)
