# 🐾 Stray Track – BBMP Stray Dog Monitoring System

## 📌 Overview

Stray Track is a web-based solution aimed at **tracking**, **monitoring**, and **managing the health** of stray dogs in urban areas. Developed as part of a civic tech initiative under the **BBMP project**, this system connects **veterinarians, NGOs, and the public** to improve the well-being and medical management of stray animals.

---

## 🎯 Objectives

- Implement a **QR code + RFID system** for real-time tracking.
- Enable **rapid medical intervention** by connecting dogs with NGOs, rescue teams, and vets.
- Provide the public a way to **scan and report** stray dogs via a mobile interface.
- Maintain **digital health records**: vaccination status, treatment history, etc.
- Support **collaborative care** by enabling authorities and organizations to work together.
- Reduce disease spread through **centralized outbreak monitoring**.
- Lay the groundwork for **future IoT-based expansion** with RFID & GPS modules.

---

## 🛠️ Technologies Used

| Category     | Stack / Tools                          |
|--------------|----------------------------------------|
| Frontend     | HTML, CSS, Node.js                     |
| Backend      | Firebase Realtime Database             |
| Image Hosting| Cloudinary                             |
| QR System    | InstaScan.js for QR generation/scanning|
| API Usage    | Firebase API for dynamic updates       |

---

## 🌐 Project Link

**🔗 Website:** [Stray Track on GitHub Pages](https://notsolvablehat.github.io/strayTrack)

---

## 📁 Folder Structure (Emoji Version)

```markdown
📦 project-root  
├── 📂 public  
│   ├── 📄 index.html — Main homepage  
│   ├── 📄 scan.html — QR scanner interface  
│   ├── 📄 dog-info.html — Health record viewer  
├── 📂 src  
│   ├── 📄 qr-generator.js — QR tag creation logic  
│   ├── 📄 scanner.js — InstaScan configuration  
│   ├── 📄 firebase-config.js — Firebase API & DB setup  
│   └── 📄 upload.js — Data uploading and record updates  
├── 📂 styles  
│   └── 📄 styles.css — Custom styling and layout  
├── 📄 README.md  
└── 📄 package.json  
📷 Sample Features
🏠 Home page with NGO & medical team login

🔍 QR scanning module to retrieve stray dog data

📋 Form to update dog medical history, vaccinations, and status

📡 Firebase-based real-time data updates

📸 Cloudinary image integration for dog photos

🚀 Future Integration: RFID & GPS Tracking
To scale this solution, upcoming features include:

📌 Key Enhancements:
RFID Tagging: Unique dog identification with chip-based tracking.

GPS Module: Real-time geo-location for movement tracking.

IoT Sensors: Health metrics tracking & injury alerts.

AI Analytics: Predict outbreak zones, analyze movement heatmaps.
