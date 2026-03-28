# 🧠 ExamGuard AI – Online Exam Cheating Risk Predictor

> 🚀 A Cognitive–Behavioral AI System for Intelligent Exam Proctoring

---

## 📖 Table of Contents

* Overview
* Problem Statement
* Solution
* Features
* System Architecture
* Modules
* Tech Stack
* Installation
* Usage
* API Endpoints
* Project Structure
* Results
* Advantages
* Limitations
* Future Scope
* Author

---

## 🌍 Overview

With the rapid growth of online education, maintaining **academic integrity** during remote exams has become a major challenge.

Traditional proctoring systems:

* Rely on webcam surveillance
* Use rule-based detection
* Are intrusive and unreliable

👉 This project introduces a **next-gen AI system** that predicts cheating risk using **behavioral intelligence** instead of binary decisions.

---

## ❗ Problem Statement

Existing systems fail because:

* ❌ Binary output (Cheating / Not Cheating)
* ❌ High false positives
* ❌ No behavioral understanding
* ❌ Privacy-invasive monitoring

👉 **Goal:**
Build a system that outputs a **probability score (0–100%)** based on user behavior.

---

## 💡 Solution

We developed an AI-powered system that:

1. Collects behavioral data
2. Extracts meaningful features
3. Analyzes patterns
4. Predicts cheating probability

👉 Example Output:

```bash
Risk Score = 72% (Moderate Risk)
```

---

## ✨ Features

* 🔍 Real-time behavior tracking
* 🧠 AI-based risk prediction
* 📊 Interactive dashboard
* 🎯 Probability-based output (0–100%)
* 📧 Email notification system
* 🎨 Modern UI (Glassmorphism + Animations)
* ⚡ Fast & responsive

---

## 🏗️ System Architecture

```bash
User (Student)
     ↓
Webcam + Keyboard + Mouse Input
     ↓
Feature Extraction (CV + Interaction)
     ↓
Behavior Analysis Engine
     ↓
Risk Prediction Model
     ↓
Dashboard + Alerts + Email Notification
```

---

## 🧩 Modules Explanation

### 📥 1. Data Acquisition

* Captures webcam feed
* Records keyboard activity
* Tracks mouse movement

---

### 🔍 2. Feature Extraction

* Face detection
* Eye gaze tracking
* Head pose estimation
* Typing speed analysis
* Mouse idle behavior

---

### 🧠 3. Behavioral Analysis

* Detects anomalies
* Identifies unusual patterns
* Monitors cognitive load

---

### 📊 4. Risk Prediction

Uses weighted scoring:

```bash
Risk Score =
(Behavior × 40%)
+ (Performance × 25%)
+ (Environment × 20%)
+ (Interaction × 15%)
```

---

### 📈 5. Dashboard

Displays:

* Risk score
* Alerts
* Activity logs
* Student performance

---

## 🛠️ Tech Stack

### Frontend

* Next.js (App Router)
* TypeScript
* Tailwind CSS
* Framer Motion

### Backend

* Node.js / Flask

### AI/ML

* TensorFlow / PyTorch

### Computer Vision

* OpenCV
* MediaPipe

### Database

* MongoDB

---

## ⚙️ Installation

```bash
git clone https://github.com/your-username/examguard-ai.git
cd examguard-ai
npm install
npm run dev
```

---

## ▶️ Usage

1. Open the application
2. Login as Student/Admin
3. Start exam
4. System tracks behavior
5. Risk score generated
6. Admin can view dashboard

---

## 🔌 API Endpoints

### Send Email

```bash
POST /api/send-email
```

### Get Risk Data

```bash
GET /api/risk
```

---

## 📁 Project Structure

```bash
app/
 ├── login/
 ├── dashboard/
 ├── analysis/
 ├── api/
components/
contexts/
hooks/
lib/
```

---

## 📊 Results

* ✅ Real-time tracking implemented
* ✅ Risk scoring working
* ✅ Low latency (~1–2 sec)
* ✅ Detects abnormal behavior

---

## 👍 Advantages

* High accuracy
* Low false positives
* Ethical AI approach
* Scalable system

---

## ⚠️ Limitations

* Requires webcam
* Lighting dependent
* Limited dataset

---

## 🔮 Future Scope

* LSTM-based prediction models
* Cloud deployment
* LMS integration
* Improved accuracy

---

## 👨‍💻 Author

**Shaik Abdul Razak**
B.Tech CSE
Chaitanya Deemed to be University

---

## 🌐 Live Demo

👉 Coming Soon (Deploy on Vercel)

---

## ⭐ Support

If you like this project:

⭐ Star this repository
🍴 Fork it
📢 Share it

---
