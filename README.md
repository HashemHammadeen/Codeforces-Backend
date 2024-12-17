# Simple BackEnd System for Codeforces Website

## Overview  
This project is a **Simple BackEnd System** designed for a Codeforces-like website. It includes features for user management, problem submission, real-time updates, and secure authentication.  

The backend is built using **Spring Boot**, integrating various technologies like **Kafka**, **WebSocket**, **JWT tokens**, and more to ensure scalability, real-time communication, and secure user authentication.

---

## Features  
- **User Management**:  
  - Sign Up, Login, and Logout functionality.  
  - Email verification for account activation.  

- **Authentication and Authorization**:  
  - Secured using **Spring Security**.  
  - **JWT tokens** for session management.  

- **Problem Management**:  
  - Users can add and submit problems.
  - Solution beeing checked Using **Judge0**

- **Real-Time Updates**:  
  - Integrated **WebSocket** for real-time problem solution updates.  

- **Messaging Queue**:  
  - **Kafka** used for efficient message handling submissions.  

---

## Tech Stack  

- **Spring Boot**  
- **Kafka** for messaging queue  
- **WebSocket** for real-time updates  
- **Spring Security** for authentication and authorization  
- **JWT (JSON Web Tokens)** for secure token-based authentication  
- **JavaMailSender** for email verification  
- **PostgreSQL/MongoDB** for database (depending on your choice)  
- **Judge0** api for checking the solutions
