# 📝 Blog Website (Frontend)

This is the frontend of a full-stack **Blog Website** built using React. It provides a clean UI for users to create, read, update, and delete blog posts with authentication and comments support.

---

## 🚀 Features

* 🔐 User Login & Signup UI
* 🏠 Home page with blog posts
* 📝 Create & Update blog posts
* 📄 Detailed post view with comments
* 🗂️ Category-based filtering
* 📱 Responsive design using Material UI

---

## 🛠️ Tech Stack

* **React** (v17.0.2)
* **React Router DOM** (v6.3.0)
* **Material UI (MUI)** for UI components
* **Axios** for API calls
* **Emotion** for styling

---

## 📁 Project Structure

```id="3l9r2s"
client/
 ├── src/
 │   ├── components/
 │   ├── context/
 │   ├── service/
 │   ├── constants/
 │   ├── utils/
 │   ├── App.js
 │   └── index.js
 ├── public/
 └── package.json
```

---

## ⚙️ Setup Instructions

### 1️⃣ Install Dependencies

```bash id="d1fj8p"
npm install
```

---

### 2️⃣ Run the App

```bash id="n7zv2l"
npm start
```

👉 App will run on:

```id="5m5c5c"
http://localhost:3000
```

---

## 🔗 Backend Connection

This frontend connects to a backend API (Node.js + Express).

👉 Make sure backend is running at:

```id="g7k9z2"
http://localhost:5000
```

👉 API calls are handled using Axios (inside `src/service/api.js`)

---

## ⚠️ Important Notes

* Ensure backend server is running before starting frontend
* Update API base URL if backend is deployed
* Works best with Node.js v16 or v18 (avoid Node v24 issues)

---

## 📦 Available Scripts

```bash id="2i8o2n"
npm start     # Runs app in development mode
npm build     # Builds app for production
npm test      # Runs tests
```

---

## 👨‍💻 Author

**Saifurrahman Khan**
GitHub: https://github.com/Saifurrahman21
LinkedIn: https://www.linkedin.com/in/saifurrahman-490a54292

---

⭐ If you like this project, give it a star!
