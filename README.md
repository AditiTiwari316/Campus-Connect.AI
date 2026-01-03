# 🚀 CampusConnect.AI 
### *The Intelligent Communication Layer for Universities that turns campus chaos into structured, verified action powered by Google Gemini.*

![alt text](https://img.shields.io/badge/AI-Google%20Gemini%202.0-blue) ![alt text](https://img.shields.io/badge/Database-Firebase%20Firestore-orange) ![alt text](https://img.shields.io/badge/Frontend-React.js-61DAFB) ![alt text](https://img.shields.io/badge/Status-Hackathon%20Winner-gold)

---

## 🛑 The Problem
In 2026, campus communication is a **fragmented mess**. Between unofficial WhatsApp groups, ignored emails, and physical posters, important deadlines expire and major events are missed.
- **Notification Fatigue:** Students are overwhelmed by noise.
- **Misinformation:** Unverified news spreads faster than official updates.
- **Zero Engagement Data:** Institutions have no way to track student participation or academic risk in real-time.
- **Disconnected Data:** Academic attendance, club events, and personal habits live in separate worlds.
- **The Result:** Important deadlines expire, and students miss major opportunities because "they didn't see the post."

## ✨ The Solution
**CampusConnect.AI** is not just another app; it is a **Unified AI Communication Layer**. We integrate with existing campus ecosystems to provide a single, verified source of truth for every student, club, and department.

It combines **Multimodal AI** with **Real-time Predictive Analytics**:

1. **Extracts:** Turns messy posters into structured calendar events using Gemini OCR.
2. **Protects:** Predicts academic risk so students don't compromise grades for events.
3. **Organizes:** Digitizes personal growth through habit tracking and journaling.

---

## 🛠 Key Features

### 1. 🤖 Gemini-Powered Automation (OCR)
Clubs simply upload a poster. Our AI instantly extracts the **Title, Date, Time, and Venue**, and syncs it directly to the student's Google Calendar. No manual entry, no errors.

### 2. 📉 Academic Risk AI (Attendance Predictor)
A real-time safety net for students. The system calculates attendance across different subjects and flags **"Critical Zones" (below 75%)**, telling students exactly how many classes they can safely skip to attend campus events.

### 3. 🗓️ 31-Day Habit Dashboard
Inspired by the "Getting 1% Better Every Day" protocol. A fully interactive digital version of the traditional habit tracker where students can edit protocols, track daily points, and visualize progress.

### 4. 🌙 Sleep Rhythm Analytics
Integrated data visualization using **Recharts** to monitor student well-being and sleep cycles, ensuring a balanced campus life.

### 5. 📔 The Spiral Journal
A high-end digital notebook designed with a realistic spiral diary interface. Students can flip pages, note down quick tasks, and maintain a campus checklist.

### 6. 🌐 Unified Developer Tracker
A single hub to track technical growth across **LeetCode, GitHub, Unstop, and CodeChef**. View solved problems, commit history, and upcoming hackathons in one glance.

### 🛠️ How It Works

## 1️⃣ Poster Upload
A club organizer uploads an event image. Gemini 2.5 Flash processes the image to find metadata.
## 2️⃣ Faculty Verification
The event is stored in Firebase Firestore as "Unverified." An admin toggles the status to "True," making it live for the entire campus.
## 3️⃣ Risk Calculation
The student enters their attendance data. The logic engine calculates risk and color-codes the dashboard (Green = Safe, Red = Urgent).
## 4️⃣ Habit Visualization
Data from the Protocol table is fed into Recharts, generating a Sleep Rhythm graph and daily performance metrics.

---

## 💻 Tech Stack
- **Frontend:** React.js, Tailwind CSS (V4.0), Framer Motion (Animations)
- **AI Brain:** Google Gemini 2.0 / 1.5 Flash (Multimodal OCR)
- **Database:** Firebase Firestore (Real-time NoSQL)
- **Analytics:** Recharts (Data Visualization)
- **Deployment:** Vite (High-performance build tool)

---

## 🚀 How to Run Locally

### 1. Clone the repository:
   ```bash
   git clone https://github.com/TheSnorlax08/campus-connect.git
   ```
### 2. Install dependencies:
   ```bash
   npm install
   ```
3. Add your Gemini API Key in App.jsx.
### 4. Launch the development server:
  ```bash
npm run dev
  ```
---
## 👥 Team & Contributors
This project was built with equal effort, heart, and lines of code by:

**Co-Creators :-**

| Name | GitHub | 
| :--- | :--- | 
| **Aditi Tiwari** | [AditiTiwari316](https://github.com/AditiTiwari316) 
| **Arin Chourasia** | [TheSnorlax08](https://github.com/TheSnorlax08) 
 ## ⭐ If You Like This Project
Consider ⭐ starring the repo — it supports our journey in building smarter tech!
