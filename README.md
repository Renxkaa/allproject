# Project Portfolio

* **Workout Tracker Application ([GitHub](https://github.com/Renxkaa/allproject/tree/main/workout-tracker) | [Demo](https://drive.google.com/file/d/1OGKFS-3z8Pz7DDzpCGa5QnFxLeKTLZmC/view?usp=sharing)):** Developed a fitness app with full CRUD functionality and modular architecture to ensure a smooth and intuitive user experience.
---

# Diary App (Flutter + Firebase)

##  Overview

Diary App เป็นแอปพลิเคชันสำหรับบันทึกไดอารี่รายวัน พัฒนาโดยใช้ **Flutter** สำหรับ Frontend และ **Firebase** สำหรับ Backend และ Authentication

ผู้ใช้สามารถ:

* สมัครสมาชิก / เข้าสู่ระบบ
* เพิ่ม แก้ไข ลบ บันทึกไดอารี่
* ดูรายการบันทึกย้อนหลัง
* จัดเก็บข้อมูลแบบ Real-time บน Cloud

---

##  Tech Stack

* Flutter
* Firebase Authentication
* Cloud Firestore
* Dart

---

##  Features

### Authentication

* Email & Password Login
* Register
* Logout

###  Diary Management

* Create diary entry
* Edit diary entry
* Delete diary entry
* Timestamp recording
* Real-time database sync

---

##  Project Structure (Example)

```
lib/
 ├── screens/
 ├── widgets/
 ├── services/
 └── main.dart
```

---

##  How to Run

1. Clone repository
2. Run `flutter pub get`
3. Setup Firebase project
4. Add google-services.json
5. Run `flutter run`

---

#  Cart Management System (Node.js + Express + Redis)

##  Overview

ระบบจัดการตะกร้าสินค้า (Shopping Cart System) พัฒนาโดยใช้ **Express.js** และ **Redis** สำหรับจัดเก็บ session และข้อมูลตะกร้าแบบรวดเร็ว

ระบบรองรับ:

* Login / Register
* เพิ่มสินค้าเข้าตะกร้า
* ลบสินค้า
* คำนวณราคารวม
* จัดเก็บข้อมูล cart แยกตาม user

---

##  Tech Stack

* Node.js
* Express.js
* Redis
* EJS
* JavaScript

---

##  Features

###  User Authentication

* Register
* Login
* Session management with Redis
  
###  Cart Features

* Add to cart
* Remove item
* Update quantity
* Calculate total price
* Store cart using Redis hash structure

Example Redis Key Structure:

```
cart:{userId}:item:{itemId}
products (hash)
```

---

##  How to Run

1. Install dependencies

   ```bash
   npm install
   ```
2. Start Redis server
3. Run server

   ```bash
   node app.js
   ```
4. Open `http://localhost:3000`

---

#  YoungToy Web Application (React)

##  Overview

YoungToy เป็นเว็บแอปพลิเคชันร้านขายของเล่นออนไลน์ พัฒนาโดยใช้ **React** สำหรับ Frontend

ระบบเน้น UI/UX ที่ใช้งานง่าย รองรับการเลือกสินค้าและจัดการตะกร้า

---

## Tech Stack

* React
* JavaScript
* CSS
* REST API (เชื่อมต่อ backend)

---

##  Features
* แสดงรายการสินค้า
* ค้นหาสินค้า
* เพิ่มสินค้าเข้าตะกร้า
* แสดงจำนวนสินค้าในตะกร้า
* Responsive Design

---

##  Project Structure

```
src/
 ├── components/
 ├── pages/
 ├── services/
 └── App.js
```

---

##  How to Run

1. Install dependencies

   ```bash
   npm install
   ```
2. Start project

   ```bash
   npm start
   ```

---

#  Summary

โปรเจคนี้ประกอบด้วย 3 ระบบหลัก:

1.  Mobile Application (Flutter + Firebase)
2.  Backend Cart System (Express + Redis)
3.  Frontend E-commerce Website (React)

แสดงให้เห็นถึงความสามารถในการพัฒนา:

* Mobile Development
* Backend Development
* Frontend Development
* Database & Session Management
* Full-stack Integration

---

 Developed for educational and portfolio purposes.

---

#  Additional AI & Software Projects

###  Diabetes Prediction

* ระบบทำนายความเสี่ยงโรคเบาหวานจากข้อมูลผู้ใช้
* ใช้ Machine Learning ในการวิเคราะห์ข้อมูล
* ฝึกการทำ Data Processing และ Model Evaluation

**Tech Stack:**

* Python
* Pandas / NumPy
* Scikit-learn
* Matplotlib / Seaborn
* Jupyter Notebook


---

###  Handwritten Text Recognition

* ระบบรู้จำตัวอักษรจากลายมือ
* ใช้ Image Processing และ Deep Learning
* ฝึกการจัดการข้อมูลภาพและโมเดล AI

**Tech Stack:**

* Python
* TensorFlow / Keras
* OpenCV
* NumPy
* Matplotlib

---

###  Sudoku Game

* เกม Sudoku สำหรับฝึกตรรกะและการคิดเชิงอัลกอริทึม
* พัฒนา Logic การตรวจสอบคำตอบ
* ฝึก Problem Solving และ Algorithm Design

**Tech Stack:**

* JavaScript / Python (ตามเวอร์ชันที่พัฒนา)
* HTML / CSS (กรณี Web Version)
* Algorithm Design (Backtracking)


---

###  Mushroom Classification Web App

* เว็บแอปสำหรับจำแนกชนิดเห็ดจากภาพ
* ออกแบบเพื่อช่วยตัดสินใจด้านความปลอดภัยของอาหาร
* พัฒนา Web Interface ร่วมกับระบบจำแนกภาพ

**Tech Stack:**

* Python
* TensorFlow / PyTorch
* Flask / FastAPI
* HTML / CSS / JavaScript
* CNN (Convolutional Neural Network)


---

###  Workout Tracker Application

* แอปสำหรับบันทึกและติดตามการออกกำลังกาย
* เน้นการออกแบบ UX/UI และการจัดการข้อมูลผู้ใช้
* ฝึกการพัฒนาแอปพลิเคชันเชิงใช้งานจริง

**Tech Stack:**

* Flutter
* Dart
* Firebase / Firestore
* Provider / State Management


---

 Developed for educational and portfolio purposes.

