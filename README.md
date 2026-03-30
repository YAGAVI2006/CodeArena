# 💻 CodeArena – AI-Powered Real-Time Coding Platform

## 🚀 Overview

**CodeArena** is an AI-powered real-time coding platform designed to help students enhance their programming skills through practice, competition, and intelligent guidance.

It provides an interactive environment where users can write, execute, and analyze code, participate in live coding battles, and track their performance through analytics.

---

## 🎯 Objective

* Improve coding skills through continuous practice
* Enable real-time coding competitions
* Provide AI-based assistance for better learning
* Track and analyze student performance

---

## 🔥 Key Features

### 💻 Code Editor & Execution

* Integrated code editor
* Supports multiple programming languages (Java, Python)
* Real-time code execution using Judge0 API

---

### 🤖 AI Assistant

* Explains code logic step-by-step
* Suggests improvements and optimizations
* Helps debug errors

---

### ⚔️ Real-Time Coding Battles

* Live contests between students
* Timer-based challenges
* Instant result comparison

---

### 🏆 Live Leaderboard

* Dynamic ranking system
* Updates in real-time using WebSockets

---

### 📊 Performance Analytics

* Tracks accuracy and progress
* Displays solved problems and ranking trends

---

### 🔐 Plagiarism Detection (Advanced Feature)

* Detects similarity between codes
* Ensures fair competition

---

## 🛠️ Tech Stack

* **Frontend:** HTML, CSS, JavaScript (or React)
* **Backend:** Java (Spring Boot)
* **Database:** MySQL
* **Real-Time Communication:** WebSockets
* **Code Execution:** Judge0 API
* **AI Integration:** OpenAI / Gemini API

---

## 🧱 System Architecture

```
Frontend (User Interface)
        ↓
Backend (Spring Boot APIs)
        ↓
Code Execution (Judge0 API)
        ↓
AI Processing (OpenAI/Gemini)
        ↓
Database (MySQL)
        ↓
WebSocket Server → Real-time Leaderboard
```

---

## 🗄️ Database Design

### Users Table

* id
* name
* email
* password

### Problems Table

* id
* title
* description
* test_cases

### Submissions Table

* id
* user_id
* problem_id
* code
* result
* score

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```
git clone https://github.com/your-username/codearena-plus.git
cd codearena-plus
```

---

### 2️⃣ Backend Setup (Spring Boot)

* Open in IntelliJ / VS Code
* Configure MySQL database
* Update `application.properties`

```
spring.datasource.url=jdbc:mysql://localhost:3306/codearena
spring.datasource.username=root
spring.datasource.password=your_password
```

---

### 3️⃣ Run Backend

```
mvn spring-boot:run
```

---

### 4️⃣ Frontend Setup

* Open frontend folder
* Run using Live Server / npm

---

### 5️⃣ API Configuration

* Add Judge0 API key
* Add OpenAI/Gemini API key

---

## 📸 Demo Workflow

1. User registers/logs in
2. Selects a coding problem
3. Writes and submits code
4. Code is evaluated automatically
5. AI provides feedback
6. Leaderboard updates instantly

---

## 🧠 Future Enhancements

* Multi-language support (C++, JavaScript)
* Team coding battles
* Mobile app version
* Voice-based AI assistant

---

## 🏆 Use Cases

* College coding contests
* Placement preparation
* Online coding practice platforms

---

## 👨‍💻 Author

**Yagavi S**
B.Tech Information Technology
VSB Engineering College

---

## 📌 Conclusion

CodeArena is a complete AI-powered learning and evaluation platform that combines real-time interaction, intelligent feedback, and competitive coding to enhance student performance and engagement.

---
