# SkillSync - Quiz & Event Management System

SkillSync is a secure, PHP-based web application that allows administrators to create events and quizzes, and users to participate in quizzes. It includes role-based authentication, YouTube video embedding, quiz questions, real-time scoring, and styled dashboards.

## 🔧 Features

- User and Admin authentication system
- Admins can:
  - Add, edit, delete events
  - Add, edit, delete quizzes and quiz questions
- Users can:
  - View events
  - Take quizzes and see instant results
- YouTube video integration with each event
- Transparent and modern UI design using `style.css`

---

## 🗂️ Folder Structure

```
/dashboard/
│
├── admin/
│   ├── quiz.php
│   ├── quiz_add.php
│   ├── quiz_edit.php
│
├── user/
│   └── events/
│       ├── add-event.php
│       ├── edit-event.php
│
├── index.php
├── take_quiz.php
│
/includes/
│   ├── database.php         # Database connection and queries
│   ├── helpers.php          # Utility functions (flash, session, etc.)
│   ├── menu.php             # Navigation bar
│   ├── footer.php
│   └── system_message.php   # Displays success/error messages
│
/actions/
│   ├── events.php           # Add/edit/delete event & comment actions
│   ├── quiz.php             # Quiz CRUD logic
│   └── take_quiz.php        # Handles quiz answers
│
/assets/
│   └── css/
│       └── style.css        # Styling for all pages
```

---

## ✅ Requirements

- PHP 7.x or later
- MySQL/MariaDB
- XAMPP or similar local server
- Web browser (Chrome, Firefox, etc.)

---

## 🚀 Setup Instructions

1. **Clone or download the project:**

   ```bash
   git clone https://github.com/yourusername/skillsync.git
   ```

2. **Import the SQL database:**

   - Open **phpMyAdmin**
   - Create a database: `userdb`
   - Import the provided `.sql` file

3. **Run the server:**

   - Start Apache and MySQL from XAMPP
   - Open your browser and go to:  
     `http://localhost/dashboard/`

4. **Login credentials:**

   - Default Admin:  
     `Email: admin@example.com`  
     `Password: admin123`

---

## ✨ Styling

- The UI uses a custom `style.css` file with:
  - Glassmorphism background
  - Custom buttons, input styling
  - Responsive layout
  - Quiz page and dashboard with consistent design

---

## 📌 To-Do / Future Features

- Password encryption (bcrypt)
- User registration page
- Quiz timer
- Export quiz results
- Email notifications

---

## 📄 License

This project is open-source and free to use under the MIT License.

---

## 👨‍💻 Author

**Alexandru Turcanu**  
Email: turcanualexandru504@gmail.com  
Location: Northampton, UK  
