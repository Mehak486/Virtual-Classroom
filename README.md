# Virtual Classroom

A full-stack Virtual Classroom application designed to provide an interactive platform for online learning, communication, and classroom management.

## 🚀 Features

* User authentication with Signup and Login
* Secure JWT-based authentication
* Virtual classroom environment
* Real-time communication using Socket.IO
* Interactive classroom functionality
* MongoDB database integration
* Responsive React frontend
* Node.js and Express.js backend
* API-based communication between frontend and backend

## 🛠️ Technologies Used

### Frontend

* React.js
* Vite
* Redux Toolkit
* React Router
* Axios
* Tailwind CSS
* Lucide React
* Socket.IO Client

### Backend

* Node.js
* Express.js
* MongoDB
* Mongoose
* JWT
* bcryptjs
* Socket.IO
* Multer

## 📁 Project Structure

```text
Virtual-Classroom/
│
├── backend/
│   ├── src/
│   ├── server.js
│   ├── package.json
│   └── .env
│
├── frontend/
│   ├── src/
│   ├── package.json
│   └── ...
│
├── .gitignore
└── README.md
```

## ⚙️ Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/Mehak486/Virtual-Classroom.git
cd Virtual-Classroom
```

### 2. Setup Backend

```bash
cd backend
npm install
```

Create a `.env` file inside the `backend` folder:

```env
MONGO_URI=mongodb://127.0.0.1:27017/virtual_classroom
PORT=8000
JWT_SECRET=your_secret_key
```

Start the backend:

```bash
npm run dev
```

The backend will run on:

```text
http://localhost:8000
```

### 3. Setup Frontend

Open another terminal:

```bash
cd frontend
npm install
npm run dev
```

The frontend will run on:

```text
http://localhost:5173
```

## 🔐 Environment Variables

For security, `.env` is excluded from GitHub using `.gitignore`.

Do not upload passwords, secret keys, database credentials, or other sensitive information.

## 👩‍💻 Author

**Mehak Sharma**

GitHub: https://github.com/Mehak486
