AI KYC Document Intelligence System

# 🧠 AI KYC Document Intelligence System

An AI-powered KYC document intelligence platform built using PyTorch, YOLOv8, OCR, and Streamlit.

This project can:

- Detect important regions from Aadhaar/PAN cards
- Extract user details using OCR
- Store extracted data in a database
- Save profile images separately
- Generate unique user IDs
- Provide a modern Streamlit-based dashboard

---

# 🚀 Features

## ✅ AI-Based Document Understanding

- Detects:
  - Name
  - DOB
  - Aadhaar Number
  - Profile Photo

## ✅ OCR Extraction

- Extracts text from detected regions

## ✅ Database Integration

- Stores extracted user information
- Generates unique IDs

## ✅ Profile Image Extraction

- Saves user profile image separately

## ✅ Streamlit Dashboard

- Upload KYC documents
- View extracted information
- Manage records

## ✅ Custom Dataset Training

- Uses custom annotated Aadhaar card dataset
- Trained using YOLOv8

---

# 🧠 Tech Stack

| Technology | Usage            |
| ---------- | ---------------- |
| PyTorch    | Deep Learning    |
| YOLOv8     | Object Detection |
| EasyOCR    | Text Extraction  |
| OpenCV     | Image Processing |
| Streamlit  | Web Dashboard    |
| SQLite     | Database         |
| Python     | Backend          |

---

# 📂 Project Structure

```plaintext
ai-kyc-intelligence/
│
├── app/
│   ├── streamlit_app.py
│
├── dataset/
│   ├── train/
│   ├── valid/
│   ├── test/
│   └── data.yaml
│
├── extracted/
│   ├── photos/
│   └── text/
│
├── models/
│
├── training/
│   ├── train.py
│
├── utils/
│
├── database/
│
├── requirements.txt
├── README.md
└── .gitignore
🔥 Workflow
Upload ID Card
        ↓
YOLOv8 Detects Regions
        ↓
Crop Important Areas
        ↓
OCR Extracts Text
        ↓
Data Cleaning
        ↓
Store Data in Database
        ↓
Generate Unique User ID
🧠 Object Detection Classes
Class ID	Label
0	photo
1	name
2	dob
3	aadhaar_no
🚀 Installation
1️⃣ Clone Repository
git clone <your_repo_link>
cd ai-kyc-intelligence
2️⃣ Create Virtual Environment
Windows
python -m venv venv
venv\Scripts\activate
3️⃣ Install Dependencies
pip install -r requirements.txt
🚀 Dataset Preparation
Collect Aadhaar card images
Mask sensitive information
Annotate using Roboflow
Export dataset in YOLOv8 format
🚀 Model Training
python training/train.py
🚀 Run Streamlit App
streamlit run app/streamlit_app.py
🔥 Future Improvements
PAN Card Support
Face Matching
Fake ID Detection
Multi-language OCR
AI Avatar KYC Integration
Real-time Webcam Verification
⚠️ Important Notes
Do NOT upload real Aadhaar/PAN data publicly
Dataset folders are excluded from Git
This project is for educational and research purposes
👨‍💻 Author

Tanish Gupta

⭐ Project Goal

To build a real-world AI-powered KYC document intelligence system that can later integrate with:

AI Avatar Verification
Automated Onboarding Systems
Banking KYC Pipelines
Identity Intelligence Platforms
```
