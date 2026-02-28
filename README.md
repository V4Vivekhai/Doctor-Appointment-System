# 🩺 Prescripto — Doctor Appointment System

A full-stack web application that allows patients to book doctor appointments online, while doctors and admins can manage schedules, appointments, and profiles efficiently.

---

## 🚀 Features

* 👤 User authentication (Patient / Doctor / Admin)
* 📅 Book and manage appointments
* 🧑‍⚕️ Doctor dashboard
* 🛠️ Admin panel to manage doctors & appointments
* 💳 Online payment integration
* 📱 Responsive UI

---

## 🛠️ Tech Stack

**Frontend:**

* React
* Tailwind CSS
* Vite

**Backend:**

* Node.js
* Express.js

**Database:**

* MongoDB

**Other Tools:**

* Cloudinary (image uploads)
* JWT Authentication

---

## 📂 Project Structure

```
prescripto/
│
├── frontend/   → User web app  
├── admin/      → Admin & doctor panel  
├── backend/    → API & server  
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/prescripto.git
cd prescripto
```

### 2️⃣ Install dependencies

#### Backend

```bash
cd backend
npm install
npm run server
```

#### Frontend

```bash
cd frontend
npm install
npm run dev
```

#### Admin Panel

```bash
cd admin
npm install
npm run dev
```

---

## 🔐 Environment Variables

Create a `.env` file inside **backend/** and add:

```
PORT=5000  
MONGO_URI=your_mongodb_connection  
JWT_SECRET=your_secret  
CLOUDINARY_API_KEY=your_key  
```

---

## 🎯 Use Cases

* Patients can find doctors and book appointments
* Doctors can manage schedules and appointments
* Admin can manage platform data

---

## 📌 Future Improvements

* Notifications (Email/SMS)
* Video consultation
* Advanced analytics dashboard

---

## 👨‍💻 Author

**Vivek Khurana**
Full Stack Developer (MERN)

---

## ⭐ If you like this project

Give it a ⭐ on GitHub

---
