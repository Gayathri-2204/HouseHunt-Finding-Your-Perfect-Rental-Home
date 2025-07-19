# 🏠 HouseHunt – Finding Your Perfect Rental Home

HouseHunt is a web app designed to help users find their ideal rental homes. Users can search based on location, budget, and preferences, view detailed property info, and make booking or inquiry requests. It offers an easy and interactive experience for house seekers.

🎥 [Watch Demo Video](https://github.com/Gayathri-2204/HouseHunt-Finding-Your-Perfect-Rental-Home/tree/main/Video)

---

## 📘 Project Overview

**HouseHunt** is a full-stack web application built using the **MERN Stack** (MongoDB, Express.js, React.js, Node.js). It streamlines the rental process by connecting homeowners with potential tenants through an intuitive platform. 

- 🧑‍💼 **Renters** can browse and book properties  
- 🏘️ **Owners** can manage listings and approve bookings  
- 🛡️ **Admins** oversee all user and property activities

This project was developed during the **SmartBridge Internship** as part of a practical training experience.

---

## 👥 Team Information

- **🆔 Team ID:** `LTVIP2025TMID55971`  
- **👥 Team Size:** 4 Members  

### 🔹 Team Members:

- 💼 **Macharla Reshma Sri** — *Team Leader*  
  🔗 [LinkedIn Profile](https://www.linkedin.com/in/macharlareshmasri5)

- 💼 **Appanabhotla Janani** — *Team Member*  
  🔗 [LinkedIn Profile](https://www.linkedin.com/in/janani-appanabhotla-409626302)

- 💼 **Gunturu Lakshmi Gayathri** — *Team Member*  
  🔗 [LinkedIn Profile](https://www.linkedin.com/in/gunturu-lakshmi-gayathri1444362a7)

- 💼 **Gudivaka Srija** — *Team Member*  
  🔗 [LinkedIn Profile](https://www.linkedin.com/in/srija-gudivaka-60a25a349)

---

## ✨ Key Features

- 🔐 **User Authentication** – Renter, Owner, and Admin roles  
- 🏠 **Property Listings** – Add, update, delete, and view properties  
- 🔍 **Advanced Search** – Filter by location, price, and type  
- 📅 **Booking System** – Renters book, owners approve/reject  
- ⚙️ **Admin Dashboard** – Monitor all users and listings

---

## 🛠️ Tech Stack

| Technology  | Description                |
|-------------|----------------------------|
| MongoDB     | NoSQL Database             |
| Express.js  | Backend API Framework      |
| React.js    | Frontend Library           |
| Node.js     | Backend Runtime            |
| Bootstrap   | Responsive UI Framework    |
| JWT         | Token-based Authentication |

---
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

Visit: http://localhost:3000

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

## 📄 Project Templates

🗂️ [Click here to view the complete documentation folder on Google Drive](https://drive.google.com/drive/folders/1xwzjEgESzgOuzVqcWou_QP-NAqAUKMKJ?usp=sharing)

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

Gratitude to SmartBridge and our mentors for guiding us through this enriching internship experience.
---

🌱 Future Enhancements

📲 Mobile version (React Native)

📍 Google Maps integration

🔔 Notifications system

💬 Live Chat between renters and owners

📊 Admin Analytics Dashboard

## 💻 Local Setup Instructions

### ⚙️ Backend Setup

```bash

cd backend:

npm install

---

##Create a .env file inside /backend:

PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret

---

Start the backend server:

npm start

---

##🎨 Frontend Setup

---

cd frontend
npm install
npm start

---

##📁 Folder Structure

---

HouseHunt/
├── backend/
│   ├── config/
│   ├── controllers/
│   ├── middlewares/
│   ├── routes/
│   ├── schemas/
│   ├── uploads/
│   ├── .env
│   ├── index.js
│   ├── package.json
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── images/
│   │   ├── modules/
│   │   │   ├── admin/
│   │   │   ├── common/
│   │   │   ├── user/
│   │   │   ├── Owner/
│   │   │   └── renter/
│   │   ├── AllPropertiesCards.jsx
│   │   ├── App.js
│   │   ├── index.js
│   ├── .gitignore
│   ├── package.json

---

📄 Project Templates
🗂️ Click here to view the complete documentation folder on Google Drive

---

Includes:

🔹 Project Overview & Objective

🔹 Feature List and User Roles

🔹 Database Schema & DFD

🔹 Screenshots and Flowcharts

🔹 Team Contributions and Learnings

---

🙏 Gratitude
Special thanks to SmartBridge and our mentors for guiding us throughout this enriching internship experience.

🌱 Future Enhancements
📲 Mobile version (React Native)

📍 Google Maps integration

🔔 Notifications system

💬 Live Chat between renters and owners

📊 Admin Analytics Dashboard

