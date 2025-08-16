# 📄 Easy Resume Builder  

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)  
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)  
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)  
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)  
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)  
![License: MIT](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)  

**Easy Resume Builder** is a web-based application that lets you create professional resumes quickly using **predefined templates**.  
Built with **HTML, CSS, JavaScript, and PHP** (with optional MySQL for auth).  

---


---

## 🚀 Features
- Predefined, ready-to-use resume templates
- Clean, responsive UI
- Live preview while editing
- Download/export resume (PDF/print-ready)
- Optional user login & dashboard
- Stores generated files in `output/`

---

## 📦 Requirements
- PHP 7.4+ (XAMPP/WAMP/MAMP or any PHP web server)
- MySQL (only if login/auth is enabled)
- A web browser

---

## 📂 Project Structure
```
easy-resume-builder/
│-- about-us/              # About Us page
│-- contact-us/            # Contact page
│-- css/                   # Stylesheets
│-- img/                   # Images & icons
│-- login/                 # Login & authentication
│-- output/                # Generated resumes (PDFs/HTML)
│-- privacy-policy/        # Privacy policy page
│-- resume/                # Resume templates & forms
│-- resume-formatting/     # Resume formatting logic
│-- stylesheets/           # Extra stylesheets
│-- thumbnails/            # Template thumbnails

│-- .htaccess              # Apache config (optional)
│-- dash.php               # Dashboard
│-- dbconnect.php          # Database connection (edit creds if using MySQL)
│-- footer.php             # Footer component
│-- index.php              # Main entry point
│-- navbar.php             # Navbar component
│-- sitestyle.php          # Site-wide styles
│-- style.css              # Global stylesheet
│-- README.md              # This file
```

> ℹ️ Make sure the `output/` folder is **writable** so files can be generated and saved.

---

## 🛠️ Installation & Setup

### 1) Clone the repository
```bash
git clone https://github.com/your-username/easy-resume-builder.git
```

### 2) Move into the project
```bash
cd easy-resume-builder
```

### 3) Place into your local server root
- **XAMPP** → `htdocs`
- **WAMP** → `www`
- **MAMP** → `htdocs`

### 4) (Optional) Configure database
If you use authentication, open `dbconnect.php` and set your MySQL credentials (DB name, user, password).  
Create a database (e.g., `resume_builder`) and import the provided `.sql` file if available via **phpMyAdmin**:

1. Go to `http://localhost/phpmyadmin`
2. Create database `resume_builder`
3. Import the `.sql` file

### 5) Run the project
Start **Apache** (and **MySQL** if used) and open:
```
http://localhost/easy-resume-builder
```

---

## 📖 Usage
1. (If enabled) Register/Login.
2. Choose a template from the **Resume** section.
3. Enter your personal, education, and experience details.
4. Preview your resume live.
5. Export/download (PDF/print) — generated files go to `output/`.

---

## 🧩 Troubleshooting
- **Nothing downloads / file not saved** → Ensure `output/` exists and is writable.
- **Database errors** → Re-check credentials in `dbconnect.php` and confirm the database/tables exist.

---

## 🤝 Contributing
Issues, feature requests, and PRs are welcome. Please open an issue before large changes.

---

## 📜 License
Licensed under the **MIT License**.
