# 🚦 AIML-Based Traffic Management System

An AI-powered smart traffic management system developed using Artificial Intelligence, Machine Learning, Computer Vision, and Web Development technologies. The system helps monitor vehicle traffic in real-time, analyze congestion levels, and dynamically control traffic signals for better traffic flow management.

The main goal of this project is to reduce traffic congestion, improve road safety, and automate traffic signal operations using AI and Machine Learning techniques.

---

# 📌 Problem Statement

Traditional traffic systems use fixed signal timing which often creates:
- Heavy traffic congestion
- Long waiting times
- Fuel wastage
- Delays for emergency vehicles
- Inefficient traffic flow

This project solves these problems using:
- Real-time vehicle detection
- AI-based traffic analysis
- Smart signal timing adjustment
- Emergency vehicle prioritization

---

# 🎯 Objectives of the Project

The objectives of this project are:

- Detect vehicles using Artificial Intelligence
- Monitor traffic density in real-time
- Predict traffic congestion using Machine Learning
- Dynamically control traffic signals
- Reduce waiting time at traffic intersections
- Provide smart traffic management solutions for smart cities

---

# 🛠️ Technologies Used

## Frontend Technologies

### HTML
Used to create the structure of web pages like:
- Home page
- Dashboard
- Traffic monitoring page

### CSS
Used for:
- Designing UI
- Responsive layouts
- Dashboard styling
- Modern interface design

### JavaScript
Used for:
- Dynamic data updates
- API handling
- Real-time dashboard interaction

---

## Backend Technologies

### Python Flask
Flask is used as backend framework for:
- Creating APIs
- Sending traffic data to frontend
- Connecting AI model with website
- Handling requests and responses

---

## Database

### MySQL
MySQL stores:
- Vehicle count
- Traffic logs
- Congestion history
- Signal status
- User data

---

## AIML Technologies

### OpenCV
OpenCV is used for:
- Video processing
- Camera feed analysis
- Image manipulation

### YOLO (You Only Look Once)
YOLO is a real-time object detection algorithm used for:
- Vehicle detection
- Car counting
- Bike detection
- Bus detection
- Truck detection

### Scikit-learn
Used for:
- Machine Learning models
- Traffic prediction
- Congestion analysis

### Pandas & NumPy
Used for:
- Data processing
- Data analysis
- Numerical operations

---

# ⚙️ System Architecture

```text
Traffic Camera
      ↓
Video Feed Processing
      ↓
AI Vehicle Detection (YOLO + OpenCV)
      ↓
Traffic Density Calculation
      ↓
Machine Learning Prediction
      ↓
Signal Timing Decision
      ↓
Dashboard Display
```

The system continuously captures traffic footage, processes it using AI models, predicts congestion levels, and updates traffic signals dynamically.

---

# ✨ Key Features

## 🚗 Real-Time Vehicle Detection
The system detects vehicles from live camera feeds using YOLO object detection algorithm.

Detected vehicles include:
- Cars
- Bikes
- Trucks
- Buses

---

## 📊 Traffic Density Analysis
The system calculates:
- Number of vehicles
- Congestion level
- Road traffic density

Traffic density categories:
- Low
- Medium
- High

---

## 🚦 Smart Traffic Signal Control
Traffic signals are automatically adjusted based on:
- Vehicle count
- Congestion level
- Emergency vehicle presence

Example:
- Low traffic → Short green signal
- Heavy traffic → Longer green signal

---

## 🚑 Emergency Vehicle Detection
If ambulance or emergency vehicles are detected:
- Green signal priority is provided
- Traffic clearance becomes faster

---

## 📈 Machine Learning Prediction
Machine Learning algorithms predict:
- Future congestion
- Peak traffic timings
- Signal timing optimization

---

## 🌐 Web Dashboard
The website dashboard displays:
- Live traffic status
- Signal status
- Congestion level
- Vehicle count

---

# 📂 Project Structure

```text
traffic-management-system/
│
├── frontend/
│   ├── index.html
│   ├── dashboard.html
│   ├── style.css
│   └── script.js
│
├── backend/
│   ├── app.py
│   ├── routes.py
│   └── database.py
│
├── aiml/
│   ├── vehicle_detection.py
│   ├── traffic_prediction.py
│   └── model.pkl
│
├── database/
│   └── traffic.sql
│
└── README.md
```

---

# 🧠 Working of the System

## Step 1: Capture Traffic Video
Traffic cameras capture live road footage.

---

## Step 2: Vehicle Detection
YOLO AI model processes video frames and detects vehicles.

---

## Step 3: Vehicle Counting
The system counts total vehicles present on road.

---

## Step 4: Congestion Analysis
Traffic density is analyzed using:
- Vehicle count
- Road occupancy
- Traffic flow speed

---

## Step 5: ML Prediction
Machine Learning predicts:
- Traffic congestion level
- Signal timing requirement

---

## Step 6: Signal Decision
The system automatically decides:
- Green signal duration
- Red signal duration

---

## Step 7: Dashboard Update
Traffic information is displayed on web dashboard in real-time.

---

# 🗄️ Database Design

## Database Name

```sql
traffic_system
```

---

## Traffic Logs Table

```sql
CREATE TABLE traffic_logs (
    id INT PRIMARY KEY AUTO_INCREMENT,
    location VARCHAR(100),
    vehicle_count INT,
    congestion_level VARCHAR(50),
    signal_status VARCHAR(20),
    created_at TIMESTAMP DEFAULT CURRENT_TIMESTAMP
);
```

---

## Database Explanation

| Column Name | Description |
|---|---|
| id | Unique ID |
| location | Traffic junction location |
| vehicle_count | Number of vehicles detected |
| congestion_level | Low/Medium/High traffic |
| signal_status | Current signal status |
| created_at | Record creation time |

---


# 🚀 Future Enhancements

The project can be extended with:

- Accident detection system
- Number plate recognition
- Smart parking management
- Google Maps API integration
- Cloud deployment
- IoT traffic sensors
- AI-based route optimization

---


# 👨‍💻 Author

Sahil Chaudhary

---

# ⭐ Conclusion

This project demonstrates the integration of:
- Artificial Intelligence
- Machine Learning
- Computer Vision
- Web Development
- Database Management

The system provides a smart and automated solution for modern traffic management and smart city infrastructure.
