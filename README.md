# 💼 Job Portal App

A modern full-stack Job Portal built using the **MERN stack**, designed to connect job seekers and recruiters through a seamless and intuitive platform. The application provides secure authentication, role-based access, job management features, and a responsive user experience optimized for all devices.

---

## ✨ Features

### ✅ Core Features

* 🔐 Secure authentication and authorization using JWT
* 👥 Role-based access for students and recruiters
* 🌐 Fully responsive and modern UI
* ⚡ Fast client-side navigation and smooth user experience

### 🎓 Student Features

* Browse and search available job opportunities
* Apply to jobs with a simple workflow
* Track application status from the dashboard

### 🧑‍💼 Recruiter Features

* Create and manage job postings
* View applicants for posted jobs
* Update or remove job listings
* Access recruiter dashboard for job management

---

## 🎨 UI & User Experience

The frontend is designed with a modern and clean interface using **Tailwind CSS** and **shadcn/ui** components. Smooth animations powered by **Framer Motion** enhance usability and engagement.

### Highlights

* Responsive layouts for desktop, tablet, and mobile
* Clean and accessible component architecture
* Interactive transitions and animations
* Consistent design system across the application

---

## 🛠️ Tech Stack

### 🧑‍💻 Frontend

* **React.js**
* **Tailwind CSS**
* **shadcn/ui**
* **Framer Motion**
* **React Router**
* **Axios**

### 🖥️ Backend

* **Node.js**
* **Express.js**
* **MongoDB**
* **Mongoose**
* **JWT Authentication**

---

## 📁 Project Structure

```bash
job-portal/
├── client/               # Frontend application
│   ├── components/
│   ├── pages/
│   └── ...
│
├── server/               # Backend API
│   ├── routes/
│   ├── controllers/
│   ├── models/
│   └── ...
│
└── README.md
```

---

## 🔒 Authentication Flow

* Users register and log in securely using email and password
* JWT tokens are used for authentication and protected routes
* Access permissions are controlled based on user roles
* Recruiter and student functionalities are separated securely

---

## ⚙️ Getting Started

### 1. Clone the Repository

```bash
git clone <repository-url>
cd job-portal
```

---

### 2. Setup Environment Variables

Create a `.env` file inside the `server/` directory:

```bash
MONGODB_URI = ""

PORT = 8000

SECRET_KEY = ""

CLOUDINARY_API_KEY = ""
CLOUDINARY_SECRET_KEY = ""
CLOUDINARY_NAME = ""

NODE_ENV = ""
```

---

### 3. Install Dependencies

```bash
# Install frontend dependencies
cd client
npm install

# Install backend dependencies
cd ../server
npm install
```

---

### 4. Run the Application

```bash
# Start backend server
cd server
npm run dev

# Start frontend server
cd ../client
npm start
```

---

## 🚀 Application URLs

```bash
Frontend: https://jobportal-1-qxyu.onrender.com
Backend:  https://jobportal-bu10.onrender.com
```

---

## 📜 License

This project is licensed under the **MIT License**.

---

## 🙌 Contributions

Contributions, issues, and feature requests are welcome.
Feel free to fork the repository and submit pull requests.
