# React Routing – Dynamic & Protected Routes

## 📌 Project Overview
This project demonstrates **dynamic routing** and **protected routes** in a React application using **React Router DOM** and **localStorage-based authentication**.

The application behaves as a **Single Page Application (SPA)** with route-level access control.

---

## 🚀 Features
- Client-side routing using React Router
- Authentication using localStorage
- Protected routes using a custom `ProtectedRoute` component
- Dynamic routing using URL parameters
- API data fetching
- Redirect handling using `Navigate`
- Clean and simple UI

---

## 🧭 Routes & Access

| Route | Type | Description |
|------|------|------------|
| `/` | Public | Home page |
| `/login` | Public | Login page |
| `/todos` | Protected | List of todos |
| `/todos/:todoId` | Protected + Dynamic | Todo details page |

---

## 🔐 Authentication Rules
- Login credentials:
  - **Email:** `admin@gmail.com`
  - **Password:** `admin@123`
- On successful login:
  - `isLoggedIn = true` is stored in `localStorage`
  - User is redirected to `/todos`
- Unauthorized access to protected routes redirects to `/login`

---

## 🔗 API Used
