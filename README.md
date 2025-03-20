# Quiz Application (Spring Boot)

## Overview
This is a **Quiz Application** built using **Spring Boot, Spring Data JPA, Spring MVC, and Spring Core**. It provides hands-on experience with full-stack development using Java and Spring technologies.

## Features
- User authentication & role-based access
- CRUD operations for quizzes & questions
- Timed quizzes with scoring system
- RESTful API endpoints
- Database integration using Spring Data JPA

## Tech Stack
- **Spring Boot** - Framework for rapid development
- **Spring MVC** - Handling web requests
- **Spring Data JPA** - ORM & database management
- **Spring Core** - Dependency injection
- **H2/MySQL** - Database storage

## Installation
### Prerequisites
- Java 17+
- Maven
- MySQL or H2 Database

### Steps to Run
1. Clone the repository:
   ```sh
   git clone https://github.com/your-repo/quiz-app.git
   ```
2. Navigate to the project directory:
   ```sh
   cd quiz-app
   ```
3. Build the application:
   ```sh
   mvn clean install
   ```
4. Run the application:
   ```sh
   mvn spring-boot:run
   ```

## API Endpoints
- `POST /api/auth/register` - User registration
- `POST /api/auth/login` - User login
- `GET /api/quizzes` - Fetch all quizzes
- `POST /api/quizzes` - Create a new quiz
- `POST /api/attempt` - Submit quiz answers

## Database Schema
- **User** (id, name, email, password, role)
- **Quiz** (id, title, description, totalMarks)
- **Question** (id, quiz_id, question_text, options, correct_answer)
- **QuizAttempt** (id, user_id, quiz_id, score)

## Future Enhancements
- Add leaderboard
- Implement difficulty levels
- Enhance UI with React/Angular

## Contribution
Feel free to fork the repo and submit pull requests. Happy coding! 🚀

