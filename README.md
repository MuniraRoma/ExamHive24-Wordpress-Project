# 📚 ExamHive24 – WordPress Educational Platform

A WordPress-based educational platform for organizing educational resources and examination-related information.

![WordPress](https://img.shields.io/badge/WordPress-CMS-21759B?style=for-the-badge&logo=wordpress&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-Backend-777BB4?style=for-the-badge&logo=php&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-Database-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-Programming-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![CSS3](https://img.shields.io/badge/CSS3-Styling-1572B6?style=for-the-badge&logo=css3&logoColor=white)

## 📖 About the Project

**ExamHive24** is a WordPress-based educational website designed to provide students with an organized platform for accessing educational resources and examination-related information.

The project uses WordPress as a Content Management System (CMS), with PHP, MySQL, HTML, CSS, and JavaScript supporting website development and customization.

## 🎯 Project Objectives

- Organize educational resources.
- Make examination-related information accessible.
- Provide simple and user-friendly navigation.
- Manage website content through WordPress.
- Demonstrate practical WordPress development skills.

## ✨ Key Features

- **Educational Resources:** Organize educational materials and learning content.
- **Examination Information:** Provide a structure for examination-related resources.
- **Content Management:** Manage content through the WordPress dashboard.
- **Customizable Design:** Customize the website using themes and CSS.
- **Plugin Support:** Extend functionality using WordPress plugins.

## 🛠️ Technologies Used

- WordPress
- PHP
- MySQL
- HTML5
- CSS3
- JavaScript
- XAMPP
- Apache

## 🏗️ System Architecture

```text
Student / Visitor
       |
       v
   Web Browser
       |
       v
  Apache Server
       |
       v
    WordPress
       |
   +---+---+
   |       |
   v       v
  Theme  Plugins
   |       |
   +---+---+
       |
       v
  MySQL Database
```

## 💻 Installation and Setup

### Prerequisites

- XAMPP
- Web browser
- Git (optional)

### 1. Clone the Repository

```bash
git clone https://github.com/MuniraRoma/ExamHive24-Wordpress-Project.git
```

### 2. Set Up XAMPP

- Start Apache and MySQL from the XAMPP Control Panel.
- Copy the project folder into the `htdocs` directory.

### 3. Create the Database

- Open `http://localhost/phpmyadmin/`.
- Create a MySQL database.
- Import the `examhive24.sql` file.

### 4. Configure WordPress

Configure the database connection in `wp-config.php`. If this file is missing, create it using `wp-config-sample.php`.

Example configuration:

```php
define('DB_NAME', 'your_database_name');
define('DB_USER', 'root');
define('DB_PASSWORD', '');
define('DB_HOST', 'localhost');
```

Replace the example values with your actual database credentials.

### 5. Run the Website

Open the following URL in your browser:

`http://localhost/ExamHive24-Wordpress-Project/`

The folder name in the URL must match the actual folder name inside `htdocs`.

## 📂 Project Structure

```text
ExamHive24-Wordpress-Project/
├── wp-admin/
├── wp-content/
├── wp-includes/
├── index.php
├── wp-config-sample.php
├── wp-login.php
├── examhive24.sql
├── .htaccess
├── .gitignore
└── README.md
```

## 🔮 Future Improvements

- Student registration and user profiles.
- Online quizzes and examinations.
- Automated result generation.
- Searchable educational resources.
- Improved mobile responsiveness.

## 🔐 Security Notes

- Do not commit database passwords or secret credentials.
- Use strong administrator passwords.
- Keep WordPress, themes, and plugins updated.
- Back up website files and the database regularly.

## 📌 Project Information

- **Project Name:** ExamHive24
- **Project Type:** Educational Website
- **CMS:** WordPress
- **Backend:** PHP
- **Database:** MySQL
- **Local Environment:** XAMPP

## 👩‍💻 Author

**Wasima Khanom Munira**

GitHub: [MuniraRoma](https://github.com/MuniraRoma)

## 📄 License

WordPress is distributed under the GNU General Public License (GPL), version 2 or later. Review third-party themes and plugins for their individual licenses.
