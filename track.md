# HRMS Lite - Project Tracking

## Project Overview
HRMS Lite - A lightweight Human Resource Management System for managing employees and attendance.

## Current Status: COMPLETED

## Tech Stack
- **Frontend**: React 18 + Vite + Tailwind CSS v4
- **Backend**: Node.js + Express.js + Sequelize
- **Database**: MySQL (hrms_lite database)

## Completed Tasks

### 2026-01-13

#### Backend Development
- [x] Set up Node.js + Express project structure
- [x] Created MySQL database connection with Sequelize
- [x] Created Employee model with validation
- [x] Created Attendance model with unique constraint
- [x] Implemented Employee CRUD APIs
- [x] Implemented Attendance APIs with filtering
- [x] Created Dashboard API for statistics
- [x] Added request validation with express-validator

#### Frontend Development
- [x] Set up React + Vite project
- [x] Configured Tailwind CSS v4 with custom theme
- [x] Created reusable UI components (Modal, Toast, etc.)
- [x] Created Dashboard page with stats cards
- [x] Created Employees page with add/delete functionality
- [x] Created Attendance page with mark/filter functionality
- [x] Implemented search and filtering
- [x] Added loading, empty, and error states

#### Testing
- [x] Tested all CRUD operations
- [x] Verified dashboard statistics update correctly
- [x] Tested attendance marking and filtering
- [x] Fixed import path issues
- [x] Fixed Tailwind CSS v4 compatibility

## Running the Application

### Backend (Port 5000)
```bash
cd backend
npm run dev
```

### Frontend (Port 5173)
```bash
cd frontend
npm run dev
```

### Database Credentials
- Host: localhost
- User: phpmyadmin
- Password: root
- Database: hrms_lite

## API Endpoints

### Dashboard
- GET /api/dashboard - Dashboard statistics

### Employees
- GET /api/employees - List employees
- POST /api/employees - Add employee
- DELETE /api/employees/:id - Delete employee

### Attendance
- GET /api/attendance - List with filter
- POST /api/attendance - Mark attendance
- GET /api/attendance/today - Today's records
- GET /api/attendance/summary - Full summary

## Deployment Status
- [ ] Deploy backend to Render
- [ ] Deploy frontend to Vercel
- [ ] Test deployed application

## Notes
- Using Tailwind CSS v4 with @tailwindcss/postcss
- Modern glassmorphism dark theme
- Responsive design
