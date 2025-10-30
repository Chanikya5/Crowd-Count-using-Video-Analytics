This project is a smart video analytics system designed to monitor and manage crowd levels in real time.
It combines computer vision, deep learning, and secure user management to deliver a full-stack solution for intelligent crowd monitoring.

With this system, users can:

🔒 Log in securely with authentication and session management

👤 Manage personal user profiles

🎥 Upload video streams and define custom monitoring zones

🧮 Track and count people using AI-based detection and tracking

📊 Visualize live crowd data through charts, heatmaps, and video overlays

🚨 Receive alerts when a crowd exceeds safe thresholds

Applicable in malls, events, stadiums, transport hubs, and public safety environments where crowd control is critical.

✨ Features
🔐 Secure User Management & Profiles

Secure Authentication with robust registration and login

Profile Page for personal info (DOB, age, gender, location, etc.)

Hashed Passwords for enhanced security

JWT-based Sessions for scalable authentication

🗺️ Zone Management

Interactive Zone Creation: Draw, edit, and save monitoring zones directly on the video frame

Persistent Storage: User-specific zone and threshold data saved in a database

📈 Real-Time Analytics

Live Dashboard with zone-wise crowd counts updated continuously

Unique ID Tracking using YOLO + DeepSORT (prevents duplicate counting)

Charts & Heatmaps for visual insights

Smart Alerts for crowd limit breaches

⚙️ Project Workflow

User Onboarding – Register and log in securely

Profile Management – View or update personal details

Video & Zone Setup – Upload videos or use webcam feed, define monitoring zones

Real-Time Monitoring – Track unique IDs and display live data

Visualization & Alerts – View trends, heatmaps, and alerts

🧩 Getting Started
✅ Prerequisites

Python 3.9+

pip (Python package manager)

Git

🖥️ Installation

Clone the repository

git clone https://github.com/Chanikya5/Crowd-Count-using-Video-Analytics.git
cd Crowd-Count-using-Video-Analytics


Create and activate a virtual environment

python -m venv venv


On Windows:

venv\Scripts\activate


On Mac/Linux:

source venv/bin/activate


Install dependencies

pip install -r requirements.txt


Run the application

python app.py


Access the app
Visit http://127.0.0.1:5000
 in your browser.

🧭 Application Walkthrough
🔑 Login & Registration

New users can register, while existing users can log in securely.
Passwords are encrypted and user data is safely stored.

👤 User Profile

After login, users can visit the Profile Page to view or edit details like date of birth, age, and gender.


🎯 Zone Manipulation Dashboard

Upload video or use webcam

Draw, name, edit, and delete zones

Preview and track live IDs with bounding boxes




📊 Live Dashboard

Zone-wise population counts

Real-time line charts

Heatmaps to visualize density

Automatic alerts for threshold breaches


🧠 Tech Stack
Category	Technologies
Languages	Python, JavaScript
Framework	Flask
Computer Vision	OpenCV, YOLO, DeepSORT
Database	SQLite
Security	Password Hashing, JWT
Visualization	Chart.js, Heatmaps
👤 Author

Chanikya Gatti
📍 India
📧 chanikya5@gmail.com

🌐 GitHub Profile
