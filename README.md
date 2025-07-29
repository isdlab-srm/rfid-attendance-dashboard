# 🛡️ RFID-Based Attendance System

A full-stack attendance management system that uses **RFID cards**, **Supabase**, and a **modern Vite + React.js dashboard** to log and visualize attendance in real-time.

---

## 🗂️ Project Structure




---

## 🚀 Features

✅ RFID-based automatic attendance  
✅ Supabase authentication and database  
✅ Real-time dashboard with charts  
✅ Attendance logs with print-ready format  
✅ Fully responsive and dark-mode ready UI  
✅ Deployed using Vercel

---

## ⚙️ Setup Guide

### 1. 📥 Clone the repository

```bash
git clone https://github.com/harshilmalhotra/rfid-attendance-system.git
cd rfid-attendance-system
npm install
```

### 3. 🔐 Setup environment variables
Create a .env file in the root folder and add your Supabase credentials:

```
VITE_SUPABASE_URL=your-supabase-url
VITE_SUPABASE_ANON_KEY=your-anon-key
VITE_API_URL=your-backend-URL
```

✨ Tip: Refer to .env.example.

### 5. 💡 Flash Arduino Sketch
Navigate to:

```
Arduino/rfid_attendance/
```
Steps:

1. Rename secrets_example.h → secrets.h
2. Fill in your Wi-Fi credentials and Supabase API details
3. Upload rfid_attendance.ino to your ESP32 or 8266

### 6. 🧪 Run the frontend
```
npm run dev
```
### 🤝 Contributions
Pull requests are welcome! Open issues for bugs or feature requests.

### 📜 License
MIT License

### 🧠 Credits
Built by Harshil Malhotra
With support from the Intelligent Systems Design Lab, SRMIST.

