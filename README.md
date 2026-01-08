# Task Manager - MERN Stack

A full-stack task management application built with the MERN (MongoDB, Express.js, React.js, Node.js) stack. This application allows users to create, read, update, and delete tasks with user authentication and authorization.

## ✨ Features

- User authentication (Register/Login/Logout)
- Create, read, update, and delete tasks
- Mark tasks as complete/incomplete
- Responsive design for all devices
- Secure API with JWT authentication
- Clean and intuitive user interface

## 🛠️ Tech Stack

- **Frontend**: React.js, React Router, Context API, Axios
- **Backend**: Node.js, Express.js
- **Database**: MongoDB with Mongoose ODM
- **Authentication**: JWT (JSON Web Tokens)
- **Styling**: CSS3 (or TailwindCSS/Material-UI - update as per your stack)

## 🚀 Getting Started

### Prerequisites

- Node.js (v14 or later)
- npm or yarn
- MongoDB Atlas account or local MongoDB installation

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yamuna1708/task-manager-mern.git
   cd task-manager-mern
   ```

2. Install server dependencies:
   ```bash
   cd server
   npm install
   ```

3. Install client dependencies:
   ```bash
   cd ../client
   npm install
   ```

### Environment Variables

Create a `.env` file in the server directory and add the following:

```
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
NODE_ENV=development
```

### Running the Application

1. Start the backend server:
   ```bash
   cd server
   npm run dev
   ```

2. Start the React development server:
   ```bash
   cd ../client
   npm start
   ```

3. Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

## 📁 Project Structure

```
task-manager-mern/
├── client/                 # Frontend React application
│   ├── public/            # Static files
│   └── src/               # React components and logic
│       ├── components/    # Reusable UI components
│       ├── context/       # React context for state management
│       ├── pages/         # Page components
│       └── App.js         # Main App component
└── server/                # Backend Node.js/Express application
    ├── config/           # Configuration files
    ├── controllers/      # Route controllers
    ├── middleware/       # Custom middleware
    ├── models/           # MongoDB models
    ├── routes/           # API routes
    └── server.js         # Main server file
```

## 🔧 Available Scripts

### Server (from /server directory)
- `npm run dev` - Start the server in development mode with nodemon
- `npm start` - Start the server in production mode
- `npm test` - Run tests

### Client (from /client directory)
- `npm start` - Start the development server
- `npm test` - Run tests
- `npm run build` - Build for production

## 📄 API Endpoints

| Method | Endpoint         | Description                     |
|--------|-----------------|---------------------------------|
| POST   | /api/auth/register | Register a new user            |
| POST   | /api/auth/login    | Login user                     |
| GET    | /api/tasks        | Get all tasks for the user     |
| POST   | /api/tasks        | Create a new task              |
| PUT    | /api/tasks/:id    | Update a task                  |
| DELETE | /api/tasks/:id    | Delete a task                  |

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [MERN Stack Documentation](https://www.mongodb.com/mern-stack)
- [React Documentation](https://reactjs.org/)
- [Node.js Documentation](https://nodejs.org/en/docs/)

---
