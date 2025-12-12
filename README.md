# 🚀 Serverless Book Tracker (AWS + React + DynamoDB)

A production-ready serverless Book Tracker application built using **AWS Lambda**, **API Gateway**, **DynamoDB**, and a **React + Vite** frontend deployed on **Vercel**.

This project demonstrates strong cloud architecture, serverless backend engineering, API design, IaC, CI/CD deployment, and modern frontend development.

---

## ✨ Features

### 🔹 Frontend (React + Vite + Tailwind)
- Add books  
- Update notes / reading progress  
- Delete books  
- Responsive UI  
- Deployed on **Vercel**  

### 🔹 Backend (AWS Serverless)
- REST API with Lambda  
- CRUD operations  
- DynamoDB single-table design  
- IAM least-privilege roles  
- Deployed using **Serverless Framework**  

---

## 🧱 Architecture Overview

```
Vercel Hosting (Frontend)
        ↓
React App
        ↓
AWS API Gateway  ← HTTPS REST API
        ↓
AWS Lambda Functions
        ↓
AWS DynamoDB Table
```

Services Used:
- AWS Lambda  
- AWS API Gateway  
- AWS DynamoDB  
- AWS IAM  
- AWS CloudWatch  

---

## 📁 Folder Structure

```
backend/
frontend/
architecture/
README.md
LICENSE
CONTRIBUTING.md
```

---

## 🚀 Getting Started

### 🔧 Backend Setup (AWS + Serverless)

```bash
cd backend
npm install
serverless deploy
```

After deploy, copy your generated API URL and put it in frontend `.env`.

---

### 🖥️ Frontend Setup (React + Vite)

```bash
cd frontend
npm install
npm run dev
```

Build for production:

```bash
npm run build
```

Deploy to Vercel:

```bash
vercel deploy
```

---

## 🔐 Environment Variables

### Frontend (`.env`)
```
VITE_API_URL=https://<your-api-gateway-url>
```

### Backend (`serverless.yml`)
```
DYNAMODB_TABLE: book-tracker-table
REGION: ap-south-1
```

---

## 📦 Future Enhancements
- Add login with AWS Cognito  
- Add book search  
- Add categories/tags  
- Add analytics dashboard  

---

## 👨‍💻 Author

**Ravish Chaudhary**  
AWS | DevOps | Full Stack Developer  

GitHub · LinkedIn

---

## 📜 License
MIT License
