watch video demo Video Demo/video-demo for house hunt (1) (1).mp4
# 🏡 HouseHunt – Finding Your Perfect Rental Home

---

## 📘 Project Overview

**HouseHunt** is a full-stack web application built with the **MERN Stack (MongoDB, Express.js, React.js, Node.js)**. It streamlines the rental process by connecting homeowners with potential tenants through an intuitive platform. Renters can browse and book properties, while owners can manage listings and approve bookings. Admins oversee all user and property activity.

This project was developed during the **SmartBridge Internship** as part of a practical training experience.

---

## ✨ Key Features

- 🔐 **User Authentication** – Renter, Owner, and Admin roles  
- 🏠 **Property Listings** – Add, update, delete, and view properties  
- 🔍 **Advanced Search** – Filter properties by location, price, and type  
- 📅 **Booking System** – Renters book, owners approve/reject  
- ⚙️ **Admin Dashboard** – Monitor and control platform users and listings  

---

## 🛠️ Tech Stack

| Technology  | Description                    |
|-------------|--------------------------------|
| MongoDB     | NoSQL Database                 |
| Express.js  | Backend API Framework          |
| React.js    | Frontend Library               |
| Node.js     | Backend Runtime                |
| Bootstrap   | Responsive UI Framework        |
| JWT         | Token-based Authentication     |

---

## 💻 Local Setup Instructions
## ⚙️ Backend Setup

```cd backend
npm install
Create a .env file inside /backend:
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
Start the backend server:
npm start
```

Frontend Setup

```cd frontend
npm install
npm start
```
---

Visit: http://localhost:3000
---

## 📁 Folder Structure

```HouseHunt/
├── backend/
│ ├── config/
│ │ └── connect.js
│ ├── controllers/
│ ├── middlewares/
│ ├── routes/
│ │ ├── adminRoutes.js
│ │ ├── ownerRoutes.js
│ │ └── userRoutes.js
│ ├── schemas/
│ │ ├── bookingModel.js
│ │ ├── propertyModel.js
│ │ └── userModel.js
│ ├── uploads/
│ ├── .env
│ ├── index.js
│ ├── package.json
│ └── package-lock.json
│
├── frontend/
│ ├── public/
│ ├── src/
│ │ ├── images/
│ │ ├── modules/
│ │ │ ├── admin/
│ │ │ ├── common/
│ │ │ │ ├── ForgotPassword.jsx
│ │ │ │ ├── Home.jsx
│ │ │ │ ├── Login.jsx
│ │ │ │ └── Register.jsx
│ │ │ ├── user/
│ │ │ ├── Owner/
│ │ │ └── renter/
│ │ ├── AllPropertiesCards.jsx
│ │ ├── App.js
│ │ ├── App.css
│ │ └── index.js
│ ├── .gitignore
│ ├── package.json
│ └── package-lock.json
```
---

## 📄 Project Templates

🗂️ [Click here to view the complete documentation folder on Google Drive](https://drive.google.com/drive/folders/1xwzjEgESzgOuzVqcWou_QP-NAqAUKMKJ?usp=sharing)
---

It includes:
- 🔹 Project Overview & Objective
- 🔹 Feature List and User Roles
- 🔹 Database Schema & DFD
- 🔹 Screenshots and Flowcharts
- 🔹 Team Contributions and Learnings
---
👥 Team Members

Janani

Gayathri

Reshma

Srija

---

Gratitude to SmartBridge and our mentors for guiding us through this enriching internship experience.
---

🌱 Future Enhancements

📲 Mobile version (React Native)

📍 Google Maps integration

🔔 Notifications system

💬 Live Chat between renters and owners

📊 Admin Analytics Dashboard
