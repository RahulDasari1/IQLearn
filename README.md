# IQLearn - Elevate Your Skills, Expand Your Horizons

Welcome to **IQLearn**! This repository contains the source code for the IQLearn website, a full-stack application designed to help users elevate their skills and expand their horizons through various learning modules.

## Table of Contents

1. [Project Overview](#project-overview)
2. [Tech Stack](#tech-stack)
3. [Features](#features)
4. [Installation](#installation)
5. [Usage](#usage)
6. [Folder Structure](#folder-structure)
7. [Contributing](#contributing)
8. [License](#license)

## Project Overview

IQLearn is a platform that provides users with access to a wide range of learning materials across various disciplines. Whether you're looking to improve your professional skills or learn something new for personal growth, IQLearn has you covered.

The platform is built using modern web technologies, ensuring a responsive and interactive user experience. Users can create profiles, track their learning progress, participate in discussions, and earn certifications upon completion of courses.

## Tech Stack

### Frontend
- **React.js**: For building the user interface.
- **Redux**: For state management.
- **React Router**: For handling navigation.
- **Bootstrap**: For responsive design and layout.
- **Axios**: For handling HTTP requests to the backend.

### Backend
- **Node.js**: As the runtime environment.
- **Express.js**: As the web framework.
- **MongoDB**: As the NoSQL database.
- **Mongoose**: For MongoDB object modeling.
- **JWT (JSON Web Tokens)**: For user authentication and authorization.
- **Bcrypt**: For password hashing and security.

### DevOps
- **Docker**: For containerization of the application.
- **Nginx**: As a reverse proxy and load balancer.
- **CI/CD**: Integrated with GitHub Actions for continuous integration and deployment.

## Features

- **User Authentication**: Secure login and registration using JWT.
- **User Profiles**: Personalized profiles where users can track their progress.
- **Course Management**: Admin interface for adding, updating, and removing courses.
- **Progress Tracking**: Users can track their learning journey and achievements.
- **Discussion Forums**: Interactive forums where users can discuss course materials.
- **Responsive Design**: Fully responsive design for an optimal experience on all devices.
- **Certifications**: Users receive certificates upon completing courses.

## Installation

### Prerequisites

- Node.js (v14.x or later)
- MongoDB
- Docker (optional but recommended)

### Setup

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/iqllearn.git
   cd iqllearn
   ```

2. **Install Dependencies**:
   ```bash
   npm install
   ```

3. **Set Up Environment Variables**:
   Create a `.env` file in the root directory and add the following:
   ```bash
   NODE_ENV=development
   PORT=5000
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret_key
   ```

4. **Run the Application**:
   ```bash
   npm run dev
   ```
   This will start both the client and server in development mode.

## Usage

Once the application is up and running, you can access it in your browser at `http://localhost:5000`. Here, you can register a new account, browse available courses, enroll in courses, and participate in discussions.

For admin functionalities, you'll need to log in with an admin account.

## Folder Structure

```
iqllearn/
├── client/                 # Frontend code (React)
│   ├── public/             # Public assets
│   └── src/                # Source files
├── server/                 # Backend code (Node.js/Express)
│   ├── config/             # Configuration files
│   ├── controllers/        # Controllers
│   ├── models/             # Database models
│   ├── routes/             # API routes
│   └── middleware/         # Custom middleware
├── .env                    # Environment variables
├── docker-compose.yml      # Docker Compose configuration
└── README.md               # This README file
```

## Contributing

We welcome contributions from the community! Please fork this repository and submit a pull request with your changes. Make sure to follow our [contribution guidelines](CONTRIBUTING.md) to ensure a smooth process.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
<--
Thank you for your interest in IQLearn. Together, let's elevate skills and expand horizons!
-->
