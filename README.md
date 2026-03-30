# 🏨 Hotel Booking Website

## 📌 Overview

This project is a simple hotel booking website developed as a mini team project.
It allows users to browse rooms, learn about the hotel, and submit booking requests through an online form.

The goal of this project is to practice frontend design and basic backend integration.

---

## 🚀 Features

* 🏠 Home page with hotel introduction
* 🛏️ Room listing with images and prices
* ℹ️ About page with hotel information
* 📞 Contact page with form and location
* 📅 Booking system (form submission)
* 📱 Fully responsive design using Bootstrap

---

## 🛠️ Technologies Used

### Frontend:

* HTML5
* CSS3
* Bootstrap 5
* JavaScript

### Backend:

* FastAPI (Python)

---

## 📂 Project Structure

```
hotel-website/
│
├── index.html
├── rooms.html
├── about.html
├── contact.html
├── booking.html
│
├── css/
│   └── style.css
│
├── js/
│   └── script.js
│
├── images/
│
└── backend/
    └── main.py
```

---

## 🔄 How It Works

1. User visits the website
2. Browses rooms
3. Clicks "Book Now"
4. Fills booking form
5. Data is sent to backend using JavaScript (fetch API)
6. Backend stores booking information
7. User receives confirmation message

---

## ⚙️ How to Run the Project

### 1. Run Backend

Make sure Python is installed.

Install dependencies:

```
pip install fastapi uvicorn
```

Run server:

```
uvicorn main:app --reload
```

---

### 2. Run Frontend

* Open `index.html` in your browser
  OR
* Use Live Server (VS Code recommended)

---

## 👥 Team Members

* Member 1: Ly MengHong
* Member 2: Thoeurn Kimchhay
* Member 3: Pech Suyheng

---

## 🎯 Future Improvements

* Add database (SQLite / MySQL)
* Add login system
* Add payment integration
* Admin dashboard for bookings

---

## 📌 Conclusion

This project demonstrates a simple but functional hotel booking system with a clean UI and basic backend integration. It is designed to be easy to understand and extend for future improvements.

---
