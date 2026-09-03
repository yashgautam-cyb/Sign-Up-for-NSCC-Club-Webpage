# Sign-Up page for NSCC Membership

This project was undertaken as a prerequisite for membership in the NSC Club. It is a web-based application that allows the users to register themselves by entering the required information. It also features admin moderation on the registered members.

# Features Implemented 

User Registration & Validation: Creates new member accounts with strict input validation for empty fields, proper email formatting, and minimum password lengths.

Secure Password Hashing: Utilizes the native Web Crypto API to hash user passwords (SHA-256) before storing them, ensuring raw credentials are never exposed in browser storage.

Role-Based Access Control (RBAC): Differentiates between standard "Members" and "Admins," restricting dashboard access to authenticated administrators only.

Admin Dashboard: Provides a dynamic data table for admins to view registered users, delete accounts, promote members to admins, and demote admins back to members.

State Management: Uses localStorage to persist the simulated database of user records across browser sessions and sessionStorage to handle secure admin login states.

UI & Dark Mode: Features a responsive design with gradient backgrounds, interactive hover states, dynamic status badges, SVG icon buttons, and a persistent dark/light theme toggle.

# Technologies Used

Frontend: HTML5, CSS3, Vanilla JavaScript (ES6+)

APIs: Web Crypto API (SHA-256 Hashing)

Storage: Browser DOM Storage (localStorage and sessionStorage)

# Installation / Getting Started

Since this project relies entirely on client-side technologies, no backend server or database configuration is required.

Prerequisites:

A modern web browser (Google Chrome, Mozilla Firefox, Safari, or Microsoft Edge).

Git (optional, for cloning the repository).

Setup Commands:

Open your terminal and clone the repository:

git clone https://github.com/yashgautam-cyb/Sign-Up-for-NSCC-Club-Webpage.git

Navigate into the project directory:

cd Sign-Up-for-NSCC-Club-Webpage

# Usage Guide

Launch the Application:

Open the index.html file directly in your web browser. Alternatively, view the live deployment at [https://yashgautam-cyb.github.io/Sign-Up-for-NSCC-Club-Webpage/]

Create an Account:

Fill out the registration form with a valid email, username, and a password of at least 6 characters. The first registered user will be set to Admin.

Access the Dashboard:

Click the "Login here" link, enter your credentials, and you will be routed to the Admin Dashboard. From here, you can test promoting, demoting, or deleting other user accounts.

# License Details

This project is licensed under the MIT License. You are free to view, copy, modify, distribute, and use this code in personal or commercial projects, provided the original copyright notice is retained.