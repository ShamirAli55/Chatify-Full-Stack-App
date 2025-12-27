# JustChat

A full-stack **real-time chat application** built with the MERN stack, designed for instant messaging with secure authentication, media support, and responsive UI.

---

## 🚀 Features

* User registration & login with **JWT authentication**
* Real-time messaging using **Socket.io**
* Online users & chat presence indicators
* Upload and display profile images via **Cloudinary**
* Email notifications using **Resend**
* Responsive and modern UI with **Tailwind CSS** + **DaisyUI**
* Security features powered by **Arcjet**

---

## 🛠 Tech Stack

**Frontend:**

* React
* Context API
* Tailwind CSS
* DaisyUI

**Backend:**

* Node.js
* Express.js
* MongoDB (Mongoose)
* Socket.io
* JWT Authentication

**Third-Party Services:**

* Cloudinary (image storage)
* Resend (email notifications)
* Arcjet (security & rate limiting)

---

## 📁 Project Structure

```text
justchat/
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── socket/
│   ├── middleware/
│   ├── server.js
│   └── .env.example
├── frontend/
│   ├── src/
│   ├── public/
│   ├── package.json
│   └── .env.example
└── README.md
```

---

## ⚙️ Prerequisites

* Node.js (v16+ recommended)
* npm or yarn
* MongoDB (local or Atlas)

---

## 🔐 Environment Variables

### Backend (`backend/.env`)

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
CLIENT_URL=http://localhost:3000

# Cloudinary
CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret

# Resend
RESEND_API_KEY=your_resend_api_key

# Arcjet
ARCJET_KEY=your_arcjet_key
```

## 📦 Installation & Setup

### Clone Repository

```bash
git clone https://github.com/your-username/justchat-mern.git
cd justchat-mern
```

### Backend Setup

```bash
cd backend
npm install
npm run dev
```

Server runs at `http://localhost:5000`

### Frontend Setup

Open a new terminal:

```bash
cd frontend
npm install
npm start
```

React app runs at `http://localhost:3000`

> Make sure both frontend and backend are running simultaneously.

---

## 🔁 Real-Time Features

* Instant message delivery with **Socket.io**
* Online user presence indicators
* Chat updates without page reload

---

## 📸 Screenshots / Demo

*(Optional: Add screenshots or a link to demo video here)*

---

## 🧠 Learning Outcomes

* Built secure REST APIs with JWT authentication
* Implemented real-time chat using Socket.io
* Managed media uploads with Cloudinary
* Integrated transactional emails with Resend
* Applied security best practices with Arcjet
* Designed responsive UI with DaisyUI & Tailwind CSS

---

## 🤝 Contributing

Contributions are welcome. Fork the repo, create a branch, and submit a pull request.

---

## 📬 Contact

For feedback or collaboration, connect with me on LinkedIn.

---

⭐ If you like this project, consider giving it a star!
