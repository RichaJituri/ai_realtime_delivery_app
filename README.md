# Smart Delivery AI 🚀

Smart Delivery AI is a full-scale, production-grade **real-time delivery and fleet management platform** built using:

- **Flutter (BLoC + Clean Architecture)**
- **NestJS Backend**
- **WebSockets for real-time location updates**
- **AI integration (ETA prediction, route intelligence, chat-assistant)**
- **Map-based continuous tracking**
- **Cross-platform Android & iOS support**

This project simulates a complete real-world logistics tech stack similar to:
Zomato, Swiggy, Dunzo, Porter, Shadowfax, Delhivery, and Uber Delivery.

---

## ✨ Core Features

### 📍 Real-Time Tracking
- Continuous GPS location streaming using WebSockets  
- Customer sees rider movement live on map  
- Rider receives real-time order updates

### 🤖 AI Assistant
- ETA prediction  
- Route optimization  
- Delivery suggestions  
- Question-answer system for users  
- Built with Gemini API or Local LLM via Ollama

### 🛒 Order Management
- Order creation  
- Status tracking  
- Dispatch system  
- Notifications

### 👤 Authentication
- Signup/login with JWT  
- OTP simulation  
- Role-based access (Customer, Rider, Admin)

### 🧩 Clean Architecture
- Scalable multi-module structure  
- Repository & use-case pattern  
- Full BLoC state management

---

## 🏗️ Tech Stack

### **Frontend**
- Flutter 3.29.1 (via FVM 3.2.1)
- BLoC
- Dio
- GetIt DI
- MapLibre (Free open-source maps)
- WebSockets
- Material 3 + custom UI system

### **Backend**
- NestJS  
- WebSockets Gateway  
- JWT Auth  
- PostgreSQL / MongoDB  
- AI Engine (Gemini / Llama)  
- Role-based access control  

---

## 📦 Repository Structure

