MERN ToDo App

A ToDo app built using the MERN stack.
It also uses Redux for state management, Reactstrap for UI components, and react-transition-group for animations.

Quick Start

Add your MONGO_URI in the default.json file.

On deployment, set it as an environment variable along with jwtSecret.

Install dependencies:

# For the server

npm install

# For the client

npm run client-install

Run the app:

# Run client & server together

npm run dev

# Run only the server

npm run server

# Run only the client

npm run client

Server runs at http://localhost:5000

Client runs at http://localhost:3000

Deployment

When you deploy to Heroku, the React frontend will build automatically on the server.
You just push your code to Heroku, and it will serve the index.html from the build.
