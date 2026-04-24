# 📝 Blog Website (MERN Stack)

A full-stack **Blog Website** built using the MERN stack where users can create, update, and manage blog posts with authentication, comments, and image uploads.

---

## 🚀 Features

* 🔐 User Authentication (Login / Signup using JWT)
* ✍️ Create, Update, Delete Blog Posts
* 💬 Comment System on Posts
* 🗂️ Category-based Filtering
* 🖼️ Image Upload (Multer + GridFS)
* 📱 Responsive UI using Material UI
* ⚡ RESTful API Integration

---

## 🛠️ Tech Stack

### 🌐 Frontend

* React (v17)
* React Router DOM (v6)
* Material UI (MUI)
* Axios

### ⚙️ Backend

* Node.js
* Express.js
* MongoDB (Mongoose)
* JWT Authentication
* Bcrypt (Password Hashing)
* Multer + GridFS (File Uploads)

---

## 📁 Project Structure

```id="y72nq8"
BLOG_WEBSITE/
 ├── client/    # React frontend
 ├── server/    # Node.js backend
```

---

## ⚙️ Setup Instructions

### 1️⃣ Clone Repository

```bash id="lqj3pz"
git clone https://github.com/Saifurrahman21/BLOG_WEBSITE.git
cd BLOG_WEBSITE
```

---

## 🗄️ Database Setup

You can use either **MongoDB Atlas (Cloud)** or **Local MongoDB**.

### ☁️ Option 1: MongoDB Atlas (Recommended)

1. Create cluster on MongoDB Atlas
2. Create DB user & password
3. Allow IP: `0.0.0.0/0`
4. Copy connection string

```env id="4hhkdx"
CONNECTION_URL=mongodb+srv://username:password@cluster.mongodb.net/blogify?retryWrites=true&w=majority
```

---

### 💻 Option 2: Local MongoDB

1. Install MongoDB locally
2. Start MongoDB server

```bash id="3yjj3r"
mongod
```

3. Use connection string:

```env id="m3t6dr"
CONNECTION_URL=mongodb://localhost:27017/blogify
```

---

## 🔧 Backend Setup

```bash id="h3zq3l"
cd server
npm install
```

Create `.env` file:

```env id="y1c8he"
CONNECTION_URL=your_database_url
PORT=5000
JWT_SECRET=your_secret_key
```

Run backend:

```bash id="v2c9h1"
npm start
```

👉 Server runs at:

```id="px0q0z"
http://localhost:5000
```

---

## 🌐 Frontend Setup

```bash id="k8sx5n"
cd client
npm install
npm start
```

👉 App runs at:

```id="rj3k2s"
http://localhost:3000
```

---

## 🔗 API Integration

Frontend communicates with backend APIs using Axios.

👉 Default API Base URL:

```id="9y8d6x"
http://localhost:5000
```

---

## 🔒 Environment Variables

### Backend `.env`

```env id="2l1o0w"
CONNECTION_URL=your_mongodb_url
JWT_SECRET=your_secret
PORT=5000
```

---

## 🧪 Testing

Use:

* Postman
* Thunder Client

to test API endpoints.

---

## 🚀 Deployment

* Frontend: Vercel / Netlify
* Backend: Render / Railway
* Database: MongoDB Atlas

---

## 📸 Screenshots

*Add screenshots of your UI here (Home, Login, Create Post, etc.)*

---

## 🧠 Learning Outcomes

* Full MERN Stack Development
* REST API Design
* Authentication using JWT
* MongoDB Integration
* Image Upload using GridFS
* State Management with React

---

## 👨‍💻 Author

**Saifurrahman Khan**

* GitHub: https://github.com/Saifurrahman21
* LinkedIn: https://www.linkedin.com/in/saifurrahman-490a54292

---

## ⭐ Support

If you like this project, please give it a ⭐ on GitHub!
