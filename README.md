# 📹 ECHOLENS  
Smart AI-Powered Surveillance System – Real-time Event Detection & Reporting  

---

## 🚀 Overview  
ECHOLENS is an AI-powered surveillance system that analyzes live streams or uploaded videos, detects critical events (e.g., theft, fights, accidents, vandalism), and generates descriptive reports in real time.  
It integrates with **n8n workflows** to send automated alerts via Gmail and log event metadata into Google Sheets.  

---

## 📂 Project Structure  

```bash
.
├── app.py                       # Main Flask application (entry point)
├── utils.py                     # Utility functions
├── grad.ipynb                   # Jupyter notebook (experiments / prototyping)
├── requirements.txt             # Project dependencies
├── static/                      # Static files (CSS, JS, images)
├── templates/                   # HTML templates for Flask
├── uploads/                     # Uploaded videos
├── outputs/                     # Processed outputs & reports
├── workflow(alert+storing).json # n8n workflow file
├── yolov12n.pt                  # Pre-trained YOLO model
└── README.md                    # Documentation

```

## ⚙️ Installation  

### 1️⃣ Clone the Repository  
```bash
git clone https://github.com/Ahmed-dawood10/Echolens.git
cd Echolens
```

### 2️⃣ Create Virtual Environment & Install Dependencies
python -m venv venv
source venv/bin/activate   # On Linux/Mac
venv\Scripts\activate      # On Windows

pip install -r requirements.txt


### 3️⃣ Run Flask App
**By default, the app runs on:
👉 http://127.0.0.1:5000/**



