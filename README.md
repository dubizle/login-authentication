# 🔐 PHP Password Manager (No Database)

A simple beginner-friendly *User Authentication System* built with *PHP and JSON* — no database required.  
This project demonstrates how to build a complete login system with password reset and profile management using just *PHP, HTML, CSS, and JSON* as storage.

---

## 🚀 Features

✅ *User Registration* – Create a new account with email and password.  
✅ *User Login / Logout* – Secure login system with session handling.  
✅ *Forgot Password & Reset* – Reset your password without email links.  
✅ *Update Profile* – Change email and password directly from the dashboard.  
✅ *Change Password* – Separate page to update your password.  
✅ *JSON Storage* – All user data is stored in users.json instead of a database.  
✅ *Responsive UI* – Clean and simple interface with external CSS styling.

---

## 📁 Project Structure

password/
│
├─ index.php # Login page
├─ register.php # User registration page
├─ forgot_password.php # Forgot password form
├─ reset_password.php # Reset password form
├─ dashboard.php # User dashboard (update email, change password, etc.)
├─ change_password.php # Change password page
├─ logout.php # Logout script
├─ users.json # JSON file storing users' data
│
├─ includes/
│ └─ functions.php # Helper functions
│
└─ style/
└─ style.css # All styling for the project

## ⚙️ How It Works

1. *Register a User* – Create an account using your email and password.  
2. *Login* – Sign in with your registered credentials.  
3. *Forgot Password* – Enter your registered email to set a new password.  
4. *Dashboard* – View and update your profile information.  
5. *Change Password* – Securely update your password anytime.

---

## 💡 Technologies Used

- 🐘 PHP (Core logic & backend)
- 📁 JSON (For storing user data)
- 🖥️ HTML5 & CSS3 (Frontend UI)
- 🔐 PHP Sessions (User authentication)

---

## 📦 Installation & Setup

1. Clone this repository:

```bash
git clone https://github.com/dubizle/password.git

Place the project inside your local server directory (e.g., htdocs for XAMPP or www for Laragon).

Start your local server and open:

http://localhost/password/


📬 Contact

👨‍💻 Okorie Chidubem
📧 Email: okoriechidubem64@gmail.com

💼 LinkedIn: linkedin.com/in/okorie-chidubem-3a0149384

🐙 GitHub: github.com/dubizle

🌐 Portfolio: https://authentication.wavebnk.top

⭐ If you like this project, please consider giving it a star on GitHub!
