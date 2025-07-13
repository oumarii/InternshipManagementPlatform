# Internship Management Platform for Engineering Schools

## Overview
This platform is designed to streamline the internship management process for engineering schools. It facilitates interactions between students, professors, and administrators, making it easier to manage internship offers, applications, and poster sessions.

## Features

### For Administrators
- User management (students, professors, admins)
- Post internship offers for students
- Accept/deny internship applications submitted by students *(in progress)*
- Plan and manage poster sessions *(in progress)*
- Review student posters *(in progress)*

### For Students
- Submit internship applications
- Browse and apply to available internship offers
- Upload and manage posters *(in progress)*
- View poster session calendar *(in progress)*

### For Professors
- Review student posters *(in progress)*
- View poster session calendar *(in progress)*
- Vote on best posters *(in progress)*

## Technology Stack

### Backend
- **Language**: Java
- **Framework**: Spring Boot
- **Database**: MySQL
- **ORM**: Spring Data JPA
- **Security**: Spring Security with JWT authentication
- **API**: RESTful API

### Frontend
- **Language**: TypeScript
- **Framework**: Angular
- **UI Library**: Bootstrap
- **HTTP Client**: Angular HttpClient

## Project Structure

```
project/
├── backend/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/com/springers/
│   │   │   │   ├── CONTROLLERS/     # REST API endpoints
│   │   │   │   ├── ENTITIES/        # Domain models
│   │   │   │   ├── REPOSITORIES/    # Data access layer
│   │   │   │   ├── SECURITY/        # Authentication & authorization
│   │   │   │   ├── SERVICES/        # Business logic
│   │   │   │   └── UTILITIS/        # Helper classes
│   │   │   └── resources/           # Configuration files
│   │   └── test/                    # Unit tests
│   └── pom.xml                      # Maven dependencies
│
└── frontend/
    ├── src/
    │   ├── app/
    │   │   ├── components/          # Angular components
    │   │   ├── services/            # API services
    │   │   └── app.module.ts        # Module definitions
    │   ├── assets/                  # Static resources
    │   └── environments/            # Environment configurations
    ├── angular.json                 # Angular configuration
    └── package.json                 # NPM dependencies
```

## Screenshots
/contact%20info.png)

## Installation and Setup

### Prerequisites
- Java 17 or higher
- Maven
- Node.js and npm
- MySQL

### Backend Setup
1. Clone the repository
2. Navigate to the backend directory: `cd backend\ Stage1.0/`
3. Configure database settings in `src/main/resources/application.properties`
4. Run the application: `mvn spring-boot:run`

### Frontend Setup
1. Navigate to the frontend directory: `cd frontend_Stage1.0/`
2. Install dependencies: `npm install`
3. Start the development server: `ng serve`
4. Access the application at `http://localhost:4200`

## Development Status
This project is currently under development with several features marked as "in progress".
