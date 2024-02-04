# Intellichat

Intellichat is an intelligent chat application developed using the MERN (MongoDB, Express.js, React.js, Node.js) stack. It leverages the power of modern web technologies to provide a seamless and interactive chatting experience.

## Features

- Real-time messaging
- User authentication
- Responsive design
- Dynamic message updates
- Easy-to-use interface

## Getting Started

To run Intellichat locally, follow these steps:

### Prerequisites

Make sure you have the following installed on your machine:

- Node.js
- npm (Node Package Manager)
- MongoDB

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/nijval21/Intellichat.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Intellichat
   ```

3. Install server dependencies:

   ```bash
   cd server
   npm install
   ```

4. Install client dependencies:

   ```bash
   cd ../client
   npm install
   ```

### Configuration

1. Create a `.env` file in the `server` directory and configure the following variables:

   ```env
   PORT=3001
   MONGODB_URI=your_mongodb_connection_string
   ```

   Replace `your_mongodb_connection_string` with your actual MongoDB connection string.

2. Back in the `client` directory, create a `.env` file and configure the following variables:

   ```env
   REACT_APP_SERVER_URL=http://localhost:3001
   ```

   Adjust the server URL if you have a different setup.

### Running the Application

1. Start the server:

   ```bash
   cd ../server
   npm start
   ```

2. Open a new terminal window, navigate to the `client` directory, and start the client:

   ```bash
   cd ../client
   npm start
   ```

3. Visit [http://localhost:3000](http://localhost:3000) in your browser to access Intellichat.

Now you have successfully set up and launched Intellichat on your local machine. Feel free to explore and enhance the application according to your needs. Happy chatting!
