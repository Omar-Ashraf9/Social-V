# 📱 SocialV — Microservices-Based Social Media Platform
*A graduation project for the ITI — Java Enterprise & Web Applications Development Track*  
[Click to open SocialV.pdf](./SocialV.pdf)

---

## 📝 Overview
**SocialV** is a scalable, microservices-based social media platform designed to simulate real-world systems like Facebook.  
The platform provides core social functionalities—posting, reacting, commenting, chatting, notifications—built using distributed architecture and modern backend technologies.

---

## 🎯 Motivation
Social media applications require **scalability**, **real-time interactions**, and **high performance**.  
This project explores how microservices can provide:
- Better scalability  
- Improved maintainability  
- Real-time data processing  
- Efficient inter-service communication  
- Cloud-based media storage

---

## 🎯 Project Objectives
SocialV delivers a complete social media experience with the following components:

- **User Service** – Manage user profiles  
- **Auth Service** – Authentication & authorization  
- **Post Service** – Create, retrieve, and manage posts  
- **Like Service** – Reactions and likes  
- **Comment Service** – Add and manage comments  
- **Friend Service** – Friend requests, acceptance, and graph relationships  
- **Messaging Service** – Real-time chat using WebSockets  
- **Notification Service** – Real-time push notifications  
- **Search Service** – Full-text search  
- **Upload Service** – Manage user and post media uploads  
- **API Gateway & Service Discovery** – Inter-service coordination  

---

## 🛠️ Technologies & Tools

### **Frontend**
- Angular  
- Firebase (Cloud Firestore for media storage)

### **Backend**
- Spring Boot  
- Spring Cloud (Gateway, Discovery, Config)
- Spring Security
- Spring Data JPA (Relational DB)  
- Spring Data MongoDB (Document DB)  
- Kafka (Message Queue for async processing)  
- WebSocket (Real-time communication)

### **Additional Tools**
- Swagger (API Documentation)  
- Postman (Testing & API debugging)  
- GitHub (Version control)

---

## 📐 System Architecture

The system follows a **microservices architecture** integrating:

- API Gateway for request routing  
- Service Discovery for dynamic service registration  
- Independent microservices for each core feature  
- Kafka message queue for asynchronous communication  
- Multiple databases (Relational, Document, Graph)  
- Firebase for media storage  
- WebSockets for real-time messaging and notifications  

### Architecture Diagram   
![System Architecture](./System%20Architecture.jpg)

---

## ▶️ User Guide (Screens Included in Documentation)

- Sign Up  
- Login  
- Home Feed  
- Search Users  
- Send & Accept Friend Requests  
- Chat Interface  
- View & Edit Profile  

*(Screenshots available in pages 36–40 of the PDF.)*

---

## 🔮 Future Work

Potential enhancements:

- Smarter recommendation system  
- Enhanced analytics  
- More scalable chat backend  
- Improved media compression and streaming  
- Mobile app integration  

---

## 👥 Team Members

- Islam Ahmed Saber  
- Menna Moataz Mansour  
- Mohammed Amgad El-Sayed  
- Nada Emam Hanafy Azoz  
- Nada Mahmoud Mohammed  
- Omar Ashraf Labib  

---

## ⭐ Acknowledgements
Special thanks to the ITI instructors and supervisors for their continuous support throughout the project.
