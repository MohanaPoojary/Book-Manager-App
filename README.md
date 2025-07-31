# 📚 Book Manager App

A full-stack web application to manage books. Built with:

- 🔥 **FastAPI** (Python) for backend APIs and JWT authentication
- ⚛️ **React** (Vite) for the frontend interface
- 🔐 User registration, login (JWT-based), logout
- 📘 Add and view books
- 👤 Profile page to show logged-in user's info

---

## 🚀 Features

- Register and Login with JWT Authentication
- View user profile after login
- Add and list books (title + author)
- Logout functionality
- Protected routes using tokens

---

## 📦 Backend (FastAPI)

### 🛠️ Setup

1. **Install Python Virtual Environment Package**
   ```bash
   sudo apt update
   sudo apt install python3-venv
   ```

2. **Create Virtual Environment**
   ```bash
   python3 -m venv venv
   ```

3. **Activate Virtual Environment**
   ```bash
   source venv/bin/activate
   ```

4. **Install Required Python Packages**
   ```bash
   pip install fastapi uvicorn python-multipart
   ```

5. **Run the Backend Server**
   ```bash
   python -m uvicorn book_api.main:app --reload
   ```

---

## 🖥️ Frontend (React + Vite)

### 🛠️ Setup

1. **Install Vite React Plugin**
   ```bash
   npm install @vitejs/plugin-react --save-dev
   ```

2. **Install Dependencies**
   ```bash
   npm install
   ```

3. **Start Development Server**
   ```bash
   npm run dev
   ```

---

## 🔧 API Endpoints

- `POST /register` - User registration
- `POST /login` - User login (returns JWT token)
- `GET /profile` - Get user profile (protected)
- `POST /books` - Add a new book (protected)
- `GET /books` - List all books (protected)
- `POST /logout` - User logout

---

## 🌐 Usage

1. Start the FastAPI backend server on `http://localhost:8000`
2. Start the React frontend development server on `http://localhost:5173`
3. Register a new user or login with existing credentials
4. Add and manage your book collection
5. View your profile information

---

## 🔐 Authentication

The application uses JWT (JSON Web Tokens) for authentication. After successful login, the token is stored and used for accessing protected routes.

---

## 📋 Requirements

### Backend
- Python 3.7+
- FastAPI
- Uvicorn
- python-multipart

### Frontend
- React 18+
- Vite
- @vitejs/plugin-react

---