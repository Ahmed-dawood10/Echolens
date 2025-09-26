# ECHOLENS  
Smart AI-Powered Surveillance System – Real-time Event Detection & Reporting

## 🚀 Overview  
ECHOLENS is an AI-powered surveillance system that analyzes live streams or uploaded videos, detects critical events (e.g., theft, fights, accidents, vandalism), and generates descriptive reports in real time.  
It also integrates with **n8n workflows** to send automated alerts via Gmail and log data into Google Sheets.


## 📂 Project Structure
.
├── app.py                # Main Flask application (entry point)
├── utils.py              # Utility functions
├── grad.ipynb            # Jupyter notebook (experiments / prototyping)
├── requirements.txt      # Dependencies
├── static/               # Static files (CSS, JS, images)
├── templates/            # HTML templates for Flask
├── uploads/              # Uploaded videos
├── outputs/              # Processed outputs & reports
├── workflow(alert+storing).json # n8n workflow file
├── yolov12n.pt           # Pre-trained YOLO model
└── README.md             # Documentation
