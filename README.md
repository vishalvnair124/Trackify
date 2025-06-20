# 👥 Trackify – Employee Management System

**Trackify** is a PHP-based Employee Management System designed to efficiently manage employee details, attendance logs, and administrative operations. It leverages **PHP**, **MySQL**, and basic hardware integration for real-time tracking capabilities.

---

## 🔧 Features

- 👨‍💼 Admin panel to manage employees  
- 🧾 Employee login and log tracking  
- 📊 Attendance and activity logs  
- 📨 Email notifications using PHPMailer  
- 🤖 Optional integration with Arduino for hardware-based logging (IoT support)  

---

## 🏗️ Tech Stack

| Layer       | Technology            |
|-------------|------------------------|
| Frontend    | HTML, CSS, JS (basic)  |
| Backend     | PHP                    |
| Database    | MySQL                  |
| Email       | PHPMailer              |
| IoT         | Arduino (optional)     |

---

## 📁 Folder Structure

```
Trackify/
├── Admin/          # Admin dashboard
├── Employee/       # Employee pages
├── Emplogs/        # Attendance & activity logs
├── login/          # Login/auth system
├── common/         # Shared PHP components
├── db/             # Database connection & SQL
├── phpmailer/      # PHPMailer library
├── python/         # Optional Python-based components
├── Arduino/        # Arduino code (optional)
├── images/         # Assets/images
└── index.php       # Entry point
```

---

## ⚙️ Setup Instructions

1. Clone the repo:
```bash
git clone https://github.com/vishalvnair124/Trackify.git
```

2. Import the database in your local MySQL setup using the file in `db/`.

3. Configure your PHP server (e.g., XAMPP or WAMP) and place the project in the `htdocs/` directory.

4. Update your `db/db.php` with your MySQL credentials.

5. Launch the app in your browser:
```bash
http://localhost/Trackify/
```

---

## 💡 Note

- The project supports optional Arduino-based attendance tracking via ID tag or sensors.
- Email notifications can be customized using `phpmailer/`.

---

## 👨‍💻 Developed By

**Vishal V Nair**  
📫 [GitHub](https://github.com/vishalvnair124)

---

> A lightweight and extendable employee management system for small to mid-scale teams.
