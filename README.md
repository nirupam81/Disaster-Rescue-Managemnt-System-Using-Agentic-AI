# 🚨 Disaster Rescue Management System using Agentic AI

## 📌 Overview
This project is an AI-powered **Disaster Rescue Management System** designed to assist in emergency situations like floods. It processes images (e.g., from UAVs or cameras) to detect affected areas and identify people in need of rescue.  

The system uses a **multi-agent architecture** to analyze data, assess risk, and generate actionable rescue plans automatically.

---

## 🧠 Key Features
- 🌊 Flood detection using image analysis (water-level estimation)
- 🧍 Human detection using YOLOv8 (Ultralytics)
- 🤖 Multi-agent decision-making system
- 🚁 Automated rescue planning (boats & drones)
- 📡 Real-time communication of rescue status
- 📊 Continuous learning from previous operations

---

## 🏗️ System Architecture

The system is built using multiple intelligent agents:

### 🔍 Perception Agent
- Processes input images
- Detects humans using YOLOv8
- Estimates flood level

### 📊 Analysis Agent
- Determines risk level (Moderate / High)
- Sets rescue priority

### 🧭 Planning Agent
- Generates rescue strategy
- Decides number of boats/drones required

### ⚙️ Execution Agent
- Simulates execution of rescue plan

### 📢 Communication Agent
- Broadcasts rescue updates

### 📚 Learning Agent
- Logs data for future improvements

---

## 🛠️ Tech Stack
- **Python**
- **OpenCV**
- **YOLOv8 (Ultralytics)**
- **NumPy**
- **Pillow**
- **Google Colab**

---

## ▶️ How to Run

### 🔹 Step 1: Open in Google Colab
Upload and open the notebook file.

### 🔹 Step 2: Install Dependencies
The notebook automatically installs:
pip install ultralytics
pip install pillow-avif-plugin

### 🔹 Step 3: Upload Image
- Upload any `.jpg`, `.png`, `.webp`, or `.avif` image
- The system will process it automatically

### 🔹 Step 4: View Output
- Detected people (with bounding boxes)
- Estimated flood level
- Generated rescue plan
- Execution status

---

## 📸 Sample Output
- People detected in flooded area
- Risk level: High / Moderate
- Example plan:
  - Deploy 3 boats and 2 drones
  - OR Deploy 1 boat

---

## 🚀 Future Improvements
- 🔬 Replace mock flood detection with **DeepLabV3+ segmentation**
- 📡 Integrate real-time drone/UAV feeds
- 🌐 Build web dashboard using **Streamlit**
- 🗺️ Add GIS-based rescue planning
- 📈 Improve accuracy using real disaster datasets

---

## ⚠️ Limitations
- Flood detection is currently based on a **simple heuristic (image brightness)**
- Not trained on real flood datasets yet
- Simulation-based execution (not real deployment)

---

## 👨‍💻 Author
**Nirupam Paramanik**  
B.Tech in Computer Science Engineering (IoT)  
University of Engineering and Management, Kolkata  

---

## 💡 Project Goal
To develop an intelligent, scalable system that can assist authorities in **efficient disaster response and rescue planning using AI and computer vision**.
