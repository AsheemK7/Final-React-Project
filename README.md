# Hostel Management System – Chandigarh University

A **Hostel Management System** designed for **Chandigarh University** to efficiently manage hostel-related activities such as student registration, room allocation, fee management, complaints, and administrative control.  
The system aims to reduce manual work, improve accuracy, and provide a centralized platform for hostel operations.

---

## 📌 Features

### 👨‍🎓 Student Module
- Student registration & login
- View hostel and room details
- Room allocation status
- Hostel fee details
- Raise complaints & requests

### 🏢 Admin Module
- Admin login
- Manage students (add, update, delete)
- Room & hostel management
- Allocate / deallocate rooms
- View and resolve complaints
- Fee management

### 🛏️ Hostel Management
- Hostel details (boys/girls)
- Room availability tracking
- Capacity management

---

## 🛠️ Technologies Used

- **Frontend:** HTML, CSS, JavaScript  
- **Backend:** PHP  
- **Database:** MySQL  
- **Server:** Apache (XAMPP / WAMP)  

---

## 🗂️ Project Structure

```
Hostel-Management-System/
│
├── admin/
│   ├── dashboard.php
│   ├── manage_students.php
│   └── manage_rooms.php
│
├── student/
│   ├── login.php
│   ├── register.php
│   └── dashboard.php
│
├── database/
│   └── hostel_db.sql
│
├── assets/
│   ├── css/
│   └── js/
│
├── index.php
└── README.md
```

---

## ⚙️ Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/hostel-management-system.git
   ```

2. **Move project to server directory**
   - For XAMPP:
     ```
     C:/xampp/htdocs/
     ```

3. **Create Database**
   - Open **phpMyAdmin**
   - Create a database named:
     ```
     hostel_management
     ```
   - Import `database/hostel_db.sql`

4. **Configure Database Connection**
   - Update database credentials in:
     ```php
     config.php
     ```

5. **Run the Project**
   - Open browser and go to:
     ```
     http://localhost/hostel-management-system
     ```

---

## 🔐 Default Login Credentials

**Admin**
```
Username: admin
Password: admin123
```

**Student**
```
Register using student registration page
```

---

## 🎯 Objectives

- Digitize hostel administration
- Reduce paperwork and errors
- Improve transparency and efficiency
- Provide easy access to hostel information

---

## 🚀 Future Enhancements

- Online fee payment
- Attendance tracking
- Mobile app version
- Email/SMS notifications

---

## 🏫 Institution

**Chandigarh University**  
Department of Computer Science & Engineering

---

## 👨‍💻 Developed By

**Asheem Khan**  
B.E. CSE – Chandigarh University  

---

## 📄 License

This project is developed for **educational purposes**.
