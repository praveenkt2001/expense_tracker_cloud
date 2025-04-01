# 💰 Expense Tracker Cloud App

A full-stack cloud-based expense tracker built with **Spring Boot**, **React**, **AWS**, and **Docker**. This project allows users to manage expenses with real-time insights, PDF export, and cloud integration for receipts.

![screenshot](./screenshots/screenshot.png)

---

## 🚀 Features

- Spring Boot backend with REST APIs and JWT Auth
- React frontend with dynamic expense charts
- AWS Lambda for PDF report generation
- S3 + DynamoDB for cloud receipt storage
- Dockerized backend for deployment

---

## 🧰 Tech Stack

- **Backend:** Java (Spring Boot), JWT, AWS Lambda
- **Frontend:** React, Chart.js
- **Cloud:** AWS S3, DynamoDB, Docker
- **Database:** PostgreSQL (local) or DynamoDB (cloud)

---

## 📸 Screenshots

<p align="center">
  <img src="./screenshots/screenshot.png" alt="Expense Tracker UI" width="600"/>
</p>

---

## 📦 Getting Started

```bash
cd backend
./mvnw spring-boot:run
# Cloud-Based Expense Tracker 💰☁️

A full-stack SaaS-style app built with Spring Boot, React, and AWS for managing expenses, tracking budgets, and viewing insightful charts.

## Features
- Expense CRUD operations
- Real-time charts using Chart.js
- Secure login with JWT authentication
- Upload receipts to AWS S3
- Export reports via AWS Lambda

## Stack
- Spring Boot, PostgreSQL, JWT
- React + Redux, Chart.js
- AWS (Lambda, S3, DynamoDB)
- Docker, GitHub Actions

## Setup
1. Backend: `cd backend && ./mvnw spring-boot:run`
2. Frontend: `cd frontend && npm start`
