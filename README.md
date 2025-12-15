# ☁️ CloudShare – Next Generation File Sharing App

CloudShare is a **secure, modern, full-stack file sharing platform** that allows users to upload, manage, and share files with **public or private access**.

Built using **React & Spring Boot**, it supports **authentication, subscriptions, payments**, and a clean **SaaS-style UI**.

🔐 Secure • 🚀 Fast • 🎨 Modern • 💳 Subscription-based

---

## 🌟 Features

### 🔐 Authentication & Security
- Secure authentication using **Clerk**
- Google OAuth login
- Profile & security management
- Active device tracking

### 📁 File Management
- Upload, view, download & delete files
- Public / Private toggle for files
- Share public files via unique links
- Access files directly using shared links

### 🖥️ User Interface
- Beautiful & responsive UI using **Tailwind CSS**
- Modern icons using **Lucide Icons**
- Grid & List views for files
- Dashboard with recent files

### 💳 Subscriptions & Payments
- Free, Premium & Ultimate plans
- Credit-based file usage system
- **Razorpay integration (Test Mode)**
- Transaction history tracking

### ⚙️ Full-Stack Integration
- React frontend + Spring Boot backend
- REST APIs for file & payment handling
- MongoDB for file & metadata storage

---

## 🛠️ Tech Stack

### Frontend
- React.js
- Tailwind CSS
- Lucide Icons
- Clerk Authentication

### Backend
- Spring Boot
- Java
- MongoDB
- REST APIs

### Payments
- Razorpay (Test Mode)

---

## 📸 Screenshots

Create a folder named `screenshots` in your repository and add the images below.

![Landing Page](screenshots/LandingPage.png)
![Sign Up](screenshots/signuppage.png)
![Dashboard](screenshots/UserDashBoard.png)
![My Files](screenshots/MyFiles.png)
![Share File](screenshots/ShareFileLink.png)
![Access File](screenshots/AccessFileThroughLink.png)
![Subscriptions](screenshots/Subscriptions.png)
![Transaction History](screenshots/TransactionHistory.png)
![Profile & Security](screenshots/ProfileDetails.png)

---

## 🧑‍💻 Installation & Setup

### Prerequisites
- Node.js (v18+)
- Java 17+
- MongoDB
- Maven

---

### 🔹 Frontend Setup
```bash
cd cloudsharewebapp
npm install
npm run dev
```

Admin Panel Runs On:

```
http://localhost:5173
```

---

## ⚙️ Backend Setup (Spring Boot)

### Prerequisites

* Java 21
* Maven
* MongoDB (Local or Atlas)

### Steps

```bash
cd cloudshareapi
mvn clean install
mvn spring-boot:run
```

### Backend Runs On

```
http://localhost:8080
```

---

---

## 💳 Razorpay Integration

* Razorpay is integrated in **Test Mode**
* Payment is triggered during checkout
* Orders are confirmed after successful payment

## Environment Variables

* Create a .env file in the frontend:

* VITE_CLERK_PUBLISHABLE_KEY=your_clerk_key
* VITE_RAZORPAY_KEY=your_razorpay_test_key

---

---

## 🔮 Future Improvements

* ☁️ Cloud storage integration (AWS S3 / Firebase / Cloudinary)
* 📁 Folder support
* 🔒 File expiration & password-protected links
* 📈 Advanced analytics dashboard
* 📱 Mobile responsiveness enhancements

---


## 👨‍💻 Author

**Panyam Karthikeya**

---

## 📄 License

This project is for learning and demonstration purposes.

---

⭐ If you like this project, consider giving it a star on GitHub!





