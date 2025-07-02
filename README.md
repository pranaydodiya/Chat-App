# 🔗 Real-Time Chat App – MERN Stack | Microservices | RabbitMQ | AWS

A **scalable, production-ready real-time chat application** built with the **MERN stack**, **RabbitMQ-based microservices**, and modern DevOps tools. Designed for **speed, security, and extensibility**, it supports **OTP-based email authentication**, **real-time messaging**, and **cloud deployment on AWS EC2**.

## 🚀 Demo Video
📺 [Watch the full project walkthrough](#) *(Add YouTube or Loom link here)*

---

## 🛠️ Tech Stack

| Layer         | Technologies Used |
|---------------|-------------------|
| **Frontend**  | React.js, TypeScript, Tailwind CSS |
| **Backend**   | Node.js, Express.js |
| **Real-time** | Socket.IO |
| **Messaging Queue** | RabbitMQ |
| **Authentication** | Email-based OTP |
| **Database**  | MongoDB |
| **Caching**   | Redis |
| **DevOps**    | Docker, AWS EC2, NGINX |

---

## ✅ Core Features

- ⚡ **Real-Time Chat** powered by **Socket.IO**
- 🧱 **Microservices architecture** using **RabbitMQ**
- 🔐 **OTP-based authentication** with Email integration
- 🚀 **Deployed on AWS EC2** with production-ready optimizations
- 🧠 **Redis** for high-speed session & cache management
- 🧩 Modular backend with **Dockerized services**
- 📱 **Responsive UI** for mobile and web
- 🌐 Secure API communication using middleware and validation

---


# 1. Clone the repo
git clone https://github.com/pranaydodiya/Chat-App.git
cd Chat-App

# 2. Start all services
docker-compose up --build

# 3. Frontend
cd client
npm install
npm run dev

📊 Performance
Redis-based session store for low latency

RabbitMQ queues for async service-to-service messaging

Optimized MongoDB queries and indexes

Graceful error handling across services
