# ChatbotFarm Budget Tracker

**“Connecting Business To The Grid”**  
A free, self-hosted budget tracking app built with Hostinger Horizons — designed to help small businesses track income, expenses, and recurring costs.

---

## 🔧 Features

- Simple income & expense tracking
- Monthly budget summary dashboard
- Responsive design for desktop and mobile
- Easy to install on any cPanel or Hostinger-powered server

---

## 🚀 How to Install on Your Own Server

> 📌 **Requirements:**
> - A web hosting plan (with PHP & MySQL support)
> - File Manager or FTP access
> - MySQL Database + user credentials

### Step-by-Step Instructions

1. **Download this App**
   - Click the green **Code → Download ZIP** button on this GitHub repository

2. **Unzip Files**
   - Extract the contents of `budget-tracker.zip` to your desktop

3. **Upload Files to Your Server**
   - Use your web host’s **File Manager** (or FTP) to upload all extracted files into your desired directory (e.g. `public_html/budget`)

4. **Create MySQL Database**
   - In cPanel or Hostinger, go to “MySQL Databases”
   - Create a new database and user, and assign the user to the database
   - Save these credentials

5. **Configure Database Connection**
   - Locate the `config.php` or `.env` file (depending on app structure)
   - Update it with your MySQL credentials:
     ```php
     DB_HOST = 'localhost';
     DB_USER = 'your_db_username';
     DB_PASS = 'your_db_password';
     DB_NAME = 'your_database_name';
     ```

6. **Launch the App**
   - Visit `https://yourdomain.com/budget` to access the app
   - Follow the on-screen setup to complete initialization

---

## 👨‍💼 Powered by ChatbotFarm.ai

This app is developed and maintained by [ChatbotFarm.ai](https://chatbotfarm.ai) — a digital infrastructure company building automation and AI tools for modern businesses.

🧠 “Connecting Business To The Grid”

For consulting or customization, contact us at: [legal@chatbotfarm.ai](mailto:legal@chatbotfarm.ai)

---

## 📄 License

This app is free to use, modify, and deploy for commercial and personal use. Attribution required.

