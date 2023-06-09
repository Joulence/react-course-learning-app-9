This project is the part of the course "React - The Complete Guide" by Maximilian Schwarzmüller (https://www.udemy.com/course/react-the-complete-guide-incl-redux/).

# Event List React Project

This is a React project with a Node.js backend that allows users to manage and view events. The project includes features such as authorization, fetching data from the backend, and CRUD operations (Create, Read, Update, Delete) for event data. The routing functionality is implemented using React Router.

## Features

- User authentication: Users can create accounts, log in, and log out.
- Event management: Logged-in users can create new events, view existing events, update event details, and delete events.
- Data fetching: The React frontend communicates with the Node.js backend to fetch event data from a database.
- React Router: The project uses React Router for handling client-side routing and navigation.

## Technologies Used

The project is built using the following technologies:

- React: A JavaScript library for building user interfaces.
- Node.js: A JavaScript runtime environment that allows server-side execution of JavaScript code.
- Express.js: A web application framework for Node.js that provides features for building web servers.
- React Router: A library for declarative routing and navigation in React applications.

## Prerequisites

Before running the project, ensure that you have the following dependencies installed:

- Node.js: [https://nodejs.org](https://nodejs.org)

## Getting Started

Follow the steps below to get the project up and running:

1. Clone the repository:

```
git clone https://github.com/Joulence/react-course-learning-app-9.git
```

2. Navigate to the frontend and backend directories:

```
cd frontend
cd backend
```

3. Install the dependencies:

```
npm install
```

4. Start the Node.js backend server:

```
npm start
```

5. In a separate terminal window, start the React development server:

```
npm start
```

6. Open your browser and navigate to [http://localhost:3000](http://localhost:3000) to access the application.

## Folder Structure

The project has the following folder structure:

```
├── backend/              # Node.js backend files
│   ├── data/      # Controllers for handling API routes
│   ├── routes/           # Data models for the MongoDB database
│   ├── util/           # API routes
│   └── app.js         # Express.js server configuration
│
├── src/                  # React frontend files
│   ├── components/       # Reusable React components
│   ├── pages/            # React components representing pages
│   ├── util/         # API service for fetching data from the backend
│   ├── App.js            # Main React component
│   ├── index.js          # Entry point of the React application
│   └── ...               # Other configuration and utility files
│
└── ...
```

## Contributing

If you'd like to contribute to this project, please follow these guidelines:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Commit your changes and push the branch to your fork.
4. Submit a pull request explaining your changes.
