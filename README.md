# Study Online- Online Study Platform

## Overview
Notaion is an online study platform designed to facilitate learning and teaching through the use of modern web technologies. It provides three main roles:
- **Student**: Can browse and purchase courses.
- **Teacher**: Can view student performance.
- **Admin**: Can manage users and oversee platform activities.

This project is built using the MERN stack (MongoDB, Express, React, Node.js).
![Screenshot 2024-06-21 143523](https://github.com/Pawan2030/Study-online-Full-Stack-Project/assets/136910101/39fbeb22-f679-4d15-b1e6-1069be937e53)



## Features
- **Student**
  - Browse available courses.
  - Purchase and enroll in courses.
  - Track learning progress.
- **Teacher**
  - View all student performances.
  - Manage course content.
- **Admin**
  - View and manage all users (students, teachers).
  - Oversee platform activities and metrics.

## Technology Stack
- **Frontend**: React.js
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JSON Web Tokens (JWT)
- **State Management**: Redux

## Getting Started

### Prerequisites
- Node.js (v14 or later)
- MongoDB (local or cloud instance)

### Installation

1. **Clone the repository**
   ```sh
   git clone https://github.com/Pawan2030/studynotaion.git
   cd notaion


### API Endpoints

### Authentication

POST /api/auth/register - Register a new user
POST /api/auth/login - Login a user

### Users
GET /api/users - Get all users (Admin only)
GET /api/users/:id - Get user by ID (Admin and the user)

### Courses
GET /api/courses - Get all courses
POST /api/courses - Create a new course (Teacher only)
GET /api/courses/:id - Get course by ID
PUT /api/courses/:id - Update course by ID (Teacher only)
DELETE /api/courses/:id - Delete course by ID (Admin only)

### Student Performance
GET /api/performance - Get all student performance (Teacher only)
GET /api/performance/:studentId - Get performance by student ID (Teacher only)

### Contributing

Fork the project
Create your feature branch (git checkout -b feature/AmazingFeature)
Commit your changes (git commit -m 'Add some AmazingFeature')
Push to the branch (git push origin feature/AmazingFeature)
Open a Pull Request

License
This project is licensed under the MIT License - see the LICENSE file for details.

Contact
This project is under continuous improvement. For any queries or suggestions, please contact the author:

## Author
### Pawan 
### Email - pawanmehta2030@gmail.com


