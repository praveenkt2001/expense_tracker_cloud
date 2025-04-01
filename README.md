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