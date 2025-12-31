# 🎯 BrewSTACK-End-to-End-Caf-Machine-Application
Built a full-stack café ordering system using MySQL, FastAPI, and JavaScript, enabling real-time menu retrieval, order placement, payment tracking, order history, and sales analytics through REST APIs.

# ✅ Mysql :

# Start MYSQL backend with the following commands and run them :

use cafe_db;

SELECT * FROM items;

<img width="841" height="727" alt="image" src="https://github.com/user-attachments/assets/ac6ffa34-844e-4326-8e40-ef8e38c0c9a2" />

# ✅ Activate Virtual environment in VSCode with the following commands : 

cd (Folder_name location)

venv\Scripts\activate

# You should see:

(venv)

# ✅ Run FastAPI Backend

Go to backend folder (IMPORTANT):

cd (folder_name)

cd Cafe_backend


# ✅ Run:

uvicorn main:app --reload


# If successful, you’ll see:

Uvicorn running on http://127.0.0.1:8000

# Test Backend (Very Important)

 Open browser and check:

 Backend alive

http://127.0.0.1:8000

# Expected:

{"message":"Cafe Backend is running"}

# Menu API

http://127.0.0.1:8000/menu

You should see your items JSON from MySQL.

# Fast API:

<img width="553" height="133" alt="image" src="https://github.com/user-attachments/assets/34609dd4-d6d1-4af9-958a-7c4e6cfbfd8b" />

# Run Frontend (Live Server)
Option A: VS Code (Recommended)

1. Open index.html

2. Right click → Open with Live Server

3. Browser opens at:

http://127.0.0.1:5500

# Front end :

<img width="1853" height="926" alt="image" src="https://github.com/user-attachments/assets/adb1bffb-3f08-42be-9c04-6dc84990ed78" />

click Ctrl + c in vscode to stop fastapi running.
