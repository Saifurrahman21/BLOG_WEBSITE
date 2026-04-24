# ⚙️ Blog Website (Backend API)

This is the backend of a full-stack **Blog Website** built using Node.js, Express, and MongoDB. It provides REST APIs for authentication, blog posts, comments, and image uploads.

---

## 🚀 Features

* 🔐 User Authentication (JWT-based Login & Signup)
* ✍️ Create, Update, Delete Blog Posts
* 💬 Comment System
* 🖼️ Image Upload using GridFS
* 🔒 Password Hashing with Bcrypt
* 🌐 RESTful API Architecture

---

## 🛠️ Tech Stack

* **Node.js**
* **Express.js**
* **MongoDB (Mongoose)**
* **JWT (jsonwebtoken)** for authentication
* **Bcrypt** for password hashing
* **Multer + GridFS** for file uploads
* **CORS & Body-Parser**

---

## 📁 Project Structure

```id="f7n2kd"
server/
 ├── controller/
 ├── routes/
 ├── model/
 ├── database/
 ├── utils/
 ├── index.js
 ├── package.json
```

---

## ⚙️ Setup Instructions

### 1️⃣ Install Dependencies

```bash id="0z0qtw"
npm install
```

---

### 2️⃣ Create `.env` File

Create a `.env` file inside the `server/` folder:

```env id="q3g1o6"
CONNECTION_URL=your_mongodb_connection_string
PORT=5000
JWT_SECRET=your_secret_key
```

---

### 3️⃣ Run the Server

```bash id="c3e4tp"
npm start
```

👉 Server will run on:

```id="u6l9vm"
http://localhost:5000
```

---

## 🔗 API Endpoints (Example)

| Method | Endpoint    | Description       |
| ------ | ----------- | ----------------- |
| POST   | /signup     | Register new user |
| POST   | /login      | User login        |
| GET    | /posts      | Get all posts     |
| POST   | /create     | Create new post   |
| PUT    | /update/:id | Update post       |
| DELETE | /delete/:id | Delete post       |

---

## 🖼️ File Upload

* Uses **Multer + GridFS**
* Images are stored directly in MongoDB
* Supports large file uploads

---

## ⚠️ Important Notes

## 🗄️ Database Setup

You can use either **MongoDB Atlas (Cloud)** or **Local MongoDB**.

### ☁️ Option 1: MongoDB Atlas (Recommended)

1. Create cluster on MongoDB Atlas
2. Create DB user & password
3. Allow IP: `0.0.0.0/0`
4. Copy connection string

```env
CONNECTION_URL=mongodb+srv://username:password@cluster.mongodb.net/blogify?retryWrites=true&w=majority
```

---

### 💻 Option 2: Local MongoDB

1. Install MongoDB locally
2. Start MongoDB server

```bash
mongod
```

3. Use local connection string:

```env
CONNECTION_URL=mongodb://localhost:27017/blogify
```

---

👉 Make sure to update your `.env` file accordingly.


---

## 🔒 Environment Variables

Example:

```env id="6z3w8p"
CONNECTION_URL=mongodb+srv://username:password@cluster.mongodb.net/blogify
JWT_SECRET=your_secret
PORT=5000
```

---

## 🧪 Testing APIs

Use tools like:

* Postman
* Thunder Client (VS Code)

---

## 🚀 Deployment

* Backend can be deployed on:

  * Render
  * Railway
  * Cyclic

---

## 👨‍💻 Author

**Saifurrahman Khan**
GitHub: https://github.com/Saifurrahman21
LinkedIn: https://www.linkedin.com/in/saifurrahman-490a54292

---

⭐ If you like this project, give it a star!
