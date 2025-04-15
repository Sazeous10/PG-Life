# 🏠 PG Life

**PG Life** is a dynamic web application that helps users find and book Paying Guest (PG) accommodations across various cities in India. Built with a responsive frontend and a robust backend, PG Life provides a seamless experience for both students and working professionals searching for a place to stay.

---
## 🚀 Features

- 🌆 Search for PGs by city
- 🏘️ View detailed information about PGs (photos, amenities, prices, etc.)
- 👥 Login/Signup system for users
- 🔒 Secure user authentication
- 📦 Filter PGs by gender (Boys/Girls), price, etc.
- 📞 Contact PG owners
- 📚 Backend management using PHP & MySQL
- 💻 Fully responsive UI using Bootstrap

---

## 🛠️ Tech Stack

### Frontend
- **HTML5**
- **CSS3**
- **Bootstrap 4**
- **JavaScript**

### Backend
- **PHP**
- **MySQL**

---

## 📂 Project Structure

/pg-life/
├── css/               # Stylesheets
├── images/            # Image assets
├── js/                # JavaScript files
├── php/               # PHP backend files
├── sql/               # MySQL scripts (DB schema, seed data)
├── index.html         # Home page
├── login.php          # Login logic
├── signup.php         # Signup logic
├── dashboard.php      # PG listings page
└── ...                # Other supporting pages and files

---

## ⚙️ Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/pg-life.git
   cd pg-life
   ```

2. **Set up the database**
   - Import the SQL file located in `/sql/pg_life.sql` into your MySQL server.
   - You can use tools like phpMyAdmin or MySQL CLI.

3. **Configure database connection**
   - Open the PHP config file (e.g., `config.php`) and update your MySQL credentials:
     ```php
     $host = 'localhost';
     $user = 'root';
     $password = '';
     $database = 'pg_life';
     ```

4. **Run the project**
   - Host the project on a local server using XAMPP, WAMP, or any LAMP stack.
   - Navigate to `http://localhost/pg-life/` in your browser.

---


## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to open an issue or submit a pull request.

---
