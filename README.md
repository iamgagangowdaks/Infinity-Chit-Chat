# 🚀 Infinity Chit Chat – Backend (Node.js + Express + MongoDB)

This is the backend system for **Infinity Chit Chat**, a coding-focused social media platform designed for developers to connect, share knowledge, and collaborate.

It handles authentication, authorization, and admin functionalities with a scalable architecture.

---

## 📌 Features

* 🔐 User Registration & Login (JWT Authentication)
* 🛡️ Role-Based Access Control (User / Admin)
* 🔑 Secure Password Hashing (bcrypt)
* 🚫 Protected Routes using Middleware
* 📦 Scalable MVC Folder Structure
* ⚡ RESTful API Design

---

## 🧰 Tech Stack

* **Backend:** Node.js, Express.js
* **Database:** MongoDB (MongoDB Atlas)
* **ODM:** Mongoose
* **Authentication:** JSON Web Token (JWT)
* **Security:** bcrypt

---

## 📂 Project Structure

```
project/
├── controllers/      # Business logic
├── middleware/       # Auth & role middleware
├── models/           # Mongoose schemas
├── routes/           # API routes
├── src/
│   └── server.js     # Entry point
├── package.json
└── .env              # Environment variables
```

---

## ⚙️ Environment Variables

Create a `.env` file inside the **backend folder** and add:

```
PORT=5002
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

⚠️ Do not use quotes in `.env`

---

## 🧪 Running the Project

### 1️⃣ Install Dependencies

```bash
npm install
```

### 2️⃣ Start Server

```bash
npm start
```

### ✅ Expected Output

```
Server is running on PORT 5002
MongoDB Connected successfully
```

---

## 🌐 API Endpoints (Sample)

### 🔐 Auth Routes

* `POST /api/auth/register` → Register user
* `POST /api/auth/login` → Login user

### 👤 User Routes

* `GET /api/user/profile` → Get user profile

### 🛠️ Admin Routes

* `GET /api/admin/dashboard` → Admin access only

---

## 🚧 Future Enhancements

| Feature               | Status         |
| --------------------- | -------------- |
| 💬 Real-time Chat     | 🔄 In Progress |
| 📝 Post & Comments    | ⏳ Planned      |
| 💼 Freelancing Module | 🔥 Upcoming    |
| 📊 DSA Problems       | 🔄 In Progress |
| 🌍 Community Spaces   | 🔥 Upcoming    |

---

## 🔒 Security Practices

* Password hashing using bcrypt
* JWT-based authentication
* Protected API routes
* Environment variable protection

---

## 🧠 Learning Highlights

This project demonstrates:

* Backend architecture design
* Authentication & authorization
* Middleware usage in Express
* MongoDB integration with Mongoose
* REST API development

---

## 👨‍💻 Author

**Gangan Goda K.S.**
🎓 CSE Student | 💻 Backend Developer |

📧 Email: [gagangowdaks958@gmail.com](mailto:gagangowdaks958@gmail.com)
🔗 GitHub:[ https://github.com/iamgagangowdaks](https://github.com/iamgagangowdaks)

---

## ⭐ Support

If you like this project:

* ⭐ Star the repository
* 🍴 Fork it
* 🤝 Contribute

---

## 📜 License

This project is licensed under the **MIT License**.
