# Parking-Space-Detection-And-Record-Management

# 🚗 Parking Space Detection & Record Management System

## 📌 Project Overview
This project is a **Parking Space Detection and Record Management System** that leverages **Computer Vision, Deep Learning, and Machine Learning** to detect available parking spaces from a video feed. The system allows users to manually select parking spaces from an image, stores the model in a **pickle file**, and integrates with **PostGIS** for spatial data management.

## 🚀 Features
- **Automatic Parking Space Detection**: Analyzes an MP4 video to detect vacant and occupied parking spots.
- **Manual Space Selection**: Users can select parking spaces using an image-based selection tool.
- **Deep Learning & ML Integration**: Utilizes trained models for accurate detection.
- **PostGIS Database Integration**: Stores parking records for spatial analysis and retrieval.
- **Pickle File Model Storage**: Saves and loads trained models efficiently.

## 📂 Project Structure
```
📁 Parking_Space_Detection
│-- main.py                 # Main script to run parking detection
│-- parking_space_picker.py # Tool for manual space selection
│-- carparkpos.pkl          # Pickle file storing trained parking space model
│-- parking_video.mp4       # Input video for parking detection
│-- requirements.txt        # Dependencies
│-- README.md               # Documentation
```

## 🔧 Installation & Setup
### **1️⃣ Install Dependencies**
```sh
pip install -r requirements.txt
```

### **2️⃣ Run Parking Space Picker** (To select parking spots manually)
```sh
python parking_space_picker.py
```
- This will open an image where users can manually mark parking spaces.
- Selected spaces will be stored in `carparkpos.pkl`.

### **3️⃣ Run Main Parking Detection System**
```sh
python main.py
```
- The system will analyze the `parking_video.mp4` file to detect occupied and vacant parking spaces.
- Results will be processed and stored in PostGIS for record management.

## 📊 Technology Stack
- **Computer Vision**: OpenCV
- **Deep Learning & ML**: TensorFlow/PyTorch
- **Spatial Database**: PostGIS
- **Python & Data Processing**: Pandas, NumPy, Pickle

- **Real-time Camera Feed Integration** 📡
- **Mobile App for Live Monitoring** 📲
- **Automated Alerts for Vacant Spaces** 🚨

---
🚘 **Smart Parking Management, Powered by AI!** 🚀
