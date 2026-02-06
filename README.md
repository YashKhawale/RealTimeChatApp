# 💬 Real-Time Chat Application using Spring Boot & WebSockets

A full-stack real-time chat application built using **Spring Boot**, **WebSockets**, and **Thymeleaf**.  
This project demonstrates real-time, bidirectional communication between multiple clients using the WebSocket protocol.
It is based on STOMP (Simple Text Oriented Messaging Protocol) messaging protocol.

---

## 🚀 Features

- Real-time messaging without page refresh
- Multiple users can join and chat simultaneously
- WebSocket-based bidirectional communication
- Simple and responsive UI using Thymeleaf
- Clean MVC-based Spring Boot architecture

---

## 🛠️ Tech Stack

### Backend
- Java
- Spring Boot
- Spring WebSocket
- Spring MVC

### Frontend
- Thymeleaf
- HTML5
- CSS3
- JavaScript

### Build Tool
- Maven

---

## Project Structure

src/main/java
 └── com.example.chatapp
     ├── config        # WebSocket configuration
     ├── controller    # Message controllers
     ├── model         # Message model
     └── ChatAppApplication.java

src/main/resources
 ├── templates         # Thymeleaf HTML files
 └── application.properties

---

## How It Works

- The application establishes a WebSocket connection between the client and server.
- When a user sends a message, it is sent to the server via WebSocket.
- The server broadcasts the message to all connected clients in real time.
- Thymeleaf dynamically renders the chat interface on the client side.

---

## Getting Started

### Prerequisites
- Java 11 or higher (Java 17 recommended)
- Maven
- IDE (IntelliJ IDEA, Eclipse, or VS Code)

### Steps to Run

1. Clone the repository
   git clone https://github.com/YashKhawale/RealTimeChatApp.git

2. Navigate to the project directory
   cd spring-boot-chat-app

3. Run the application
   mvn spring-boot:run

4. Open your browser and visit
   http://localhost:8080

5. Open the application in multiple browser tabs to test real-time messaging.

---

## Use Cases

- Learning WebSockets with Spring Boot
- Understanding real-time communication
- Full-stack Java project for portfolio
- Base project for chat systems or notification services

---

## Future Enhancements

- User authentication and authorization
- Private chat rooms
- Message persistence using a database
- Typing indicators
- Online/offline user status
- Dockerization and cloud deployment

---

## Learning Outcomes

- WebSocket protocol
- Spring Boot WebSocket configuration
- Real-time message broadcasting
- Backend and frontend integration using Thymeleaf
