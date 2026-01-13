# Employee Portal Management System (EPMS)

A lightweight **Employee Portal & User Management System** built with **PHP, MySQL, HTML/CSS, and JavaScript**.  
The system provides secure authentication, employee dashboards, content management, and file upload capabilities.

## 🚀 Features

- 🔐 **Secure Authentication**
  - Login system using PHP sessions
  - Password verification with database-backed users
  - Protected routes for authenticated users

- 👤 **Employee Dashboard**
  - Personalized employee dashboard
  - Session-based access control
  - Dynamic content loading

- 🗂 **Content Management**
  - AJAX-powered content loading
  - Modular PHP structure
  - Easy extension for new features

- 📤 **File Upload System**
  - Upload and manage files securely
  - Organized uploads directory
  - Supports multiple file types

- 🖼 **Media & Assets**
  - Logos and images included
  - Custom branding support

- 📄 **Documentation**
  - Project report and PDF documentation included
  - Easy to understand system structure


## 🛠 Tech Stack

- **Backend:** PHP (PDO)
- **Database:** MySQL
- **Frontend:** HTML, CSS, JavaScript (AJAX)
- **Server:** Apache (XAMPP / LAMP / WAMP)
- **Authentication:** PHP Sessions

## 📂 Project Structure

project-TT/
│
├── project/
│ ├── auth.php # Authentication logic
│ ├── employee_dashboard.php # Employee dashboard
│ ├── content.php # Main content loader
│ ├── content_ajax.php # AJAX content handler
│ ├── logo.png
│ ├── uploads/ # Uploaded files
│ ├── pic/ # Images & assets
│ └── .git/ # Git repository
│
├── docs/
│ ├── Employee Portal Management System.pdf
│ └── raport.docx
│
└── README.md


## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

git clone https://github.com/your-username/employee-portal-management-system.git
2️⃣ Move to Server Directory
Place the project inside your web server directory:

htdocs (XAMPP)

www (WAMP)

/var/www/html (Linux)

3️⃣ Create Database
Create a MySQL database:

CREATE DATABASE user_management_system;
4️⃣ Configure Database Connection
Edit auth.php:

$host = '127.0.0.1';
$db   = 'user_management_system';
$user = 'root';
$pass = '';
5️⃣ Import Tables
Import your SQL schema (if available) or create user tables manually.

6️⃣ Run the Project
Open your browser and go to:

http://localhost/project-TT/project/
🖥 Screenshots
📌 Place screenshots inside a screenshots/ folder and update paths below.

🔐 Login Page

📊 Employee Dashboard

📁 File Upload

🔒 Security Notes
Uses PDO prepared statements to prevent SQL injection

Session-based authentication

Access control for protected pages

Upload folder should be restricted in production

📈 Future Improvements
Role-based access (Admin / Employee)

Password hashing with password_hash()

Activity logs

Responsive UI (Bootstrap / Tailwind)

REST API support

📄 License
This project is for educational purposes.
You are free to modify and use it for learning or academic projects.

👨‍💻 Author
Project TT – Employee Portal Management System
Developed as part of an academic / training project.

⭐ If you like this project, don’t forget to star the repository!
