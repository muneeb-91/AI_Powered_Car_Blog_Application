# AI Powered Car Blog App 

A full-stack MERN application that allows every registered user to write blog post individually that is relevant to cars. No need to write lengthy descriptions, now you only have to click a button and AI will write description for you.
This project is divided into two folders `frontend` (React) and `backend` (Express + Node.js).  

---

## 📷 Screenshots

![screenshot_1](https://github.com/muneeb-91/AI_Powered_Car_Blog_Application/blob/4d4ffe23c13145060fdf383140cca50a2255e7b7/screenshots/car_blog_ss1.png)

![screenshot_2](https://github.com/muneeb-91/AI_Powered_Car_Blog_Application/blob/101231cc0f83e539914b818aa8c83137912a1c0b/screenshots/car_blog_ss2.png)

![screenshot_3](https://github.com/muneeb-91/AI_Powered_Car_Blog_Application/blob/4d4ffe23c13145060fdf383140cca50a2255e7b7/screenshots/car_blog_ss3.png)

![screenshot_4](https://github.com/muneeb-91/AI_Powered_Car_Blog_Application/blob/4d4ffe23c13145060fdf383140cca50a2255e7b7/screenshots/car_blog_ss4.png)

---
## 📂 Project Structure  

```bash
root
├── backend # Express server (API)
└── frontend # React client
```
---

## 🚀 Getting Started  

### 1️⃣ Clone the Repository  

```bash
git clone https://github.com/muneeb-91/project_name.git
cd project_name
```

### 2️⃣ Backend Setup

```bash
cd backend
npm install
```
#### Create .env file inside backend

```bash
PORT=your_port_number
# MONGO_URI=your_mongo_url
CLOUDINARY_CLOUD_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
GEMINI_API_KEY=your_gemini_api_key
JWT_SECRET_KEY=your_jwt_secret_key
```

#### Run the backend
With nodemon:

```bash
nodemon server.js
```
OR with "start" script:

```bash
npm start
```
OR normally with:

```bash
node server.js
```
### 3️⃣ Frontend Setup

```bash
cd frontend
npm install
```
#### Update frontend/lib/axios.js file

```bash
update your backend url with port: e.g. http://localhost:5001/api
```

#### Run the frontend

```bash
npm run dev
```
Frontend will run at localhost:5173

---

## 📸 Features

**→ AI Driven Desription Writing**

**→ Categorized Blog Fetching**

**→ Trending Section with Trending Blogs**

**→ Professional UI Design**

---

## ⚙️ Tech Stack

**→ Frontend: React, Vite, TailwindCSS**

**→ Backend: Node.js, Express.js, MongoDB**
