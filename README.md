# 🎓 erp-web - Simple College Management Solution

## 🚀 Download the App
[![Download](https://img.shields.io/badge/Download-v1.0-blue.svg)](https://github.com/louiecoolio247-cyber/erp-web/releases)

## 🎯 Overview
The College ERP system features a Django REST API backend paired with a modern web frontend. It supports JWT authentication and offers tailored dashboards for Students, Teachers, and Admins. This application simplifies college management tasks efficiently.

## 📁 Project Structure
```
ERP APP/
├── backend/                  # Django REST API
│   ├── manage.py
│   ├── requirements.txt
│   ├── setup.bat            # Windows setup script
│   ├── setup.sh             # Linux/Mac setup script
│   ├── college_erp/         # Django project
│   └── api/                 # Django app
└── web/                     # Frontend
    ├── index.html           # Login page
    ├── css/                 # Styles
    ├── js/
    │   ├── api-client.js    # API client with JWT
    │   ├── auth.js          # Authentication
    │   └── utils.js         # Utilities
    ├── student/             # Student dashboard
    ├── teacher/             # Teacher dashboard
    └── admin/               # Admin dashboard
```

## 🚀 Quick Start

### 🔽 Step 1: Download the Application
To get started, visit the Releases page to download the latest version of the College ERP system.

[Download Here](https://github.com/louiecoolio247-cyber/erp-web/releases)

### 🛠️ Step 2: Setup Requirements
Once you have downloaded the application, follow these instructions based on your operating system:

#### For Windows Users:
1. Open the `setup.bat` file.
2. Follow the prompts to install all necessary dependencies.

#### For Linux/Mac Users:
1. Open the terminal.
2. Navigate to the directory where you extracted the files.
3. Run the command `bash setup.sh` and follow the instructions.

### 🔑 Step 3: Configure the Database
You will need to set up a database for the application. Here are the steps:

1. Create a new database in your chosen database management system (e.g., PostgreSQL, MySQL).
2. Update the database configuration in the `college_erp/settings.py` file with your database credentials.

### 💻 Step 4: Run Migrations
After configuring the database, run the following command in the terminal to set up the initial data structures:

```bash
python manage.py migrate
```

### 🌐 Step 5: Start the Server
To launch the application, you need to run the server. Here’s how:

```bash
python manage.py runserver
```

After running this command, open your web browser and go to `http://127.0.0.1:8000`. You will see the login page for the ERP system.

### 📲 Step 6: Log In
Use the credentials provided in the documentation or create a new user if prompted.

## 📝 Features
- **User-Friendly Interface:** The dashboard is easy to navigate for all roles.
- **Role-Based Access:** Each user role has access to features relevant to them.
- **Secure Authentication:** The app uses JWT tokens for secure logins.
- **Responsive Design:** The web frontend adjusts well to different screen sizes.

## 💡 Usage Tips
- Regularly check for updates on the Releases page to ensure your application remains secure and functional.
- Refer to the documentation folder for more information about using specific features.

## 💬 Support
If you run into issues, you can check the FAQ section in the documentation or reach out through GitHub issues for support.

## 🔗 Quick Links
- [Releases Page](https://github.com/louiecoolio247-cyber/erp-web/releases)
- [Documentation](https://github.com/louiecoolio247-cyber/erp-web/wiki)

Downloading and installing the College ERP system is straightforward. Follow these steps, and you will have your application running in no time. Enjoy managing your college efficiently!