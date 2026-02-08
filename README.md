# 🤖 Syvi – AI Chatbot Application

<p align="center">
  <img src="https://img.shields.io/badge/Project-AI%20Chatbot-blueviolet?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Backend-Spring%20Boot-success?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Security-JWT%20%7C%20Spring%20Security-red?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge"/>
</p>

<p align="center">
  <b>An AI-powered chatbot system with secure authentication, role-based access, and persistent chat history.</b>
</p>

---

## 🧭 Overview

**Syvi** is an **AI-powered chatbot application** designed to deliver intelligent, conversational responses through a secure and scalable backend.

Built using **Java Spring Boot**, the system demonstrates real-world backend engineering concepts such as **JWT authentication**, **role-based authorization**, **RESTful API design**, and **AI prompt handling**.

This project was developed as an **academic mini/major project** and closely mirrors production-grade backend architecture used in AI-driven applications.

---

## ✨ Key Features

| Feature | Description |
|------|------------|
| 🔐 Authentication | JWT-based login & secure APIs |
| 🧑‍💼 Authorization | Role-based access (Admin / User / Public) |
| 💬 AI Chat | Prompt-based AI interaction |
| 🧠 Chat History | Persistent storage of conversations |
| 📧 Email OTP | User verification via email |
| 🌐 CORS Enabled | Smooth frontend-backend integration |
| 🛡 Security | Spring Security + filters |
| 📄 Error Handling | Global exception handling |

---

## 🧠 System Architecture

```text
Client (Chatbot UI / Web App)
            ↓
      REST API Layer
   (Spring Boot Controllers)
            ↓
     Service & AI Logic
            ↓
      Database Layer
