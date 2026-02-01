# 🔒 ShakeUp – Personal Safety Mobile Application

**ShakeUp** is a mobile app designed to automatically alert your trusted contacts in case of danger, using sudden phone movements or voice keywords. The app enhances personal safety with real-time GPS alerts, contact management, and AI-powered danger detection.

---

## ✨ Features

ShakeUp integrates key functionalities for personal security:

### 📱 Movement-Based Alerts
- **Goal:** Detects sudden phone movements to trigger an emergency alert.
- **Technology:** Android sensors & Kotlin logic.
- **Process:** Sends alert and location automatically when sudden movements are detected.

---

### 🎙️ Voice Keyword Detection
- **Goal:** Recognizes SOS keywords like "Help" or "Aidez-moi".
- **Technology:** Whisper-small model for real-time audio processing.
- **Benefit:** Enables hands-free emergency alerts.

---

### 🌍 Real-Time Danger Prediction (AI)
- **Goal:** Checks if the current location is risky based on user profile and context.
- **Technology:** Random Forest trained on synthetic dataset (age, gender, time, GPS coordinates).
- **Performance:** Achieves 95.5% accuracy in predicting dangerous zones.
- **My Contribution:** Dataset creation, model training, and integration in the app.

---

### 🧑‍🤝‍🧑 Contact Management
- **Goal:** Add, manage, and notify trusted contacts automatically during emergencies.

---

### 🗂️ Alert History
- **Goal:** Keep track of past alerts and confirmations for reference.

---

## 🤖 AI & Machine Learning

My Contribution (AI/ML) is fully contained in a separate repository:

- **Dataset & Models:** [GeoRiskPredict – AI Models & Dataset](https://github.com/AjgagalAsma/GeoRiskPredict)
- Includes:
  - Synthetic dataset generation (age, gender, time, location)
  - Machine learning model training notebooks
  - Whisper-small integration for voice alerts

> All AI models are pre-integrated; no additional setup needed to test danger prediction or voice detection in ShakeUp.

---

## 🛠️ Tech Stack

- **Mobile App:** Kotlin, Android Studio  
- **Backend & API:** Python, FastAPI, Firebase  
- **AI / ML:** Random Forest (scikit-learn), Whisper-small  
- **Data Processing:** Python, Pandas, NumPy  

---

## 📂 Presentation & Project Overview

<p align="center">
  <img src="img/img1.jpg" alt="ShakeUp Home" width="600"/>
</p>

### 🔗 LinkedIn Post
View the project overview and photos on LinkedIn:  
[ShakeUp LinkedIn Post](https://www.linkedin.com/posts/asmae-ajgagal-07bb3a341_ia-machinelearning-projetetudiant-activity-7349831503691816960-3Vvm?utm_source=share&utm_medium=member_desktop&rcm=ACoAAFXGit8BR9rnsmcvU139bS85siADcay8xVk)

---

### 🎨 Canva Presentation
View the ShakeUp project presentation (read-only):  
[ShakeUp Canva Presentation](https://www.canva.com/design/DAGod9x1Ju8/sJAr27c6hp8u5B1puf45pQ/view)


---

## ⚙️ Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/AjgagalAsma/ShakeUp.git
cd ShakeUp
```
### 2. Open the project in Android Studio
- Import the app/ folder as a project.
- Make sure you have Kotlin and Gradle configured.
  
### 3. Run the app
- Connect an Android device or start an emulator.
- Click Run in Android Studio.
