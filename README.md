# Smart Restaurant Management System

A full-stack restaurant management system built with React + Spring Boot.

## Tech Stack

- **Frontend**: React.js (Vite)
- **Backend**: Spring Boot (Java 21)
- **Database**: MySQL
- **AI**: Ollama (llama3.2:1b) via Spring AI
- **Security**: JWT Authentication

## Features

- Owner Dashboard with AI Sales Insights
- AI Chat Assistant (Owner only)
- Accountant Dashboard with PDF Bill Generation
- Chef Dashboard
- Waiter Dashboard
- Inventory Management
- Employee Management
- Analytics & Reports

## Setup Instructions

### Backend

1. Clone the repo
2. Copy `application.yml.example` to `application.yml`
3. Fill in your credentials
4. Run MySQL and create database: `smart_restaurant_db`
5. Install Ollama: https://ollama.com/download
6. Run: `ollama run llama3.2:1b`
7. Run: `mvn spring-boot:run`

### Frontend

1. `cd smart-restaurant-frontend`
2. `npm install`
3. `npm run dev`

## Running the App

- Backend: `http://localhost:9095`
- Frontend: `http://localhost:5173`
