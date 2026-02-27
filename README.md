# 🚍 AI-Powered Assistive Bus Recognition & Smart Mobility System
<b>An intelligent accessibility-focused application that helps visually impaired and elderly commuters independently identify and board the correct bus using Computer Vision, AI filtering, and smart alerts.</b>

# 🚀 Overview
<b>Public transport environments are chaotic — crowded bus stops, moving vehicles, noisy surroundings, and small destination boards.</b>  
<b>For visually impaired and elderly commuters, identifying the correct bus often requires dependence on strangers.</b>  
<b>Traditional transport apps only show route schedules, do not assist during physical boarding, and do not provide real-time bus board recognition.</b>  
<b>This project introduces an AI-powered Assistive Mobility System that detects bus numbers in real-time and intelligently alerts users through voice, vibration, and smart route matching.</b>

# 🎯 Problem Statement
<b>Daily challenges faced by visually impaired commuters include difficulty reading bus boards, risk of boarding the wrong bus, dependency on strangers, and anxiety in crowded environments.</b>  
<b>Existing navigation apps provide static route information, lack physical-world recognition, and do not offer accessibility-first design.</b>

# 💡 Proposed Solution
<b>We developed a Hybrid Recognition + Route Intelligence Engine that combines Computer Vision, Smart Filtering, Route Matching, and Accessibility Mode.</b>  
<b>Instead of just scanning text: Scan → Understand → Match → Alert.</b>  
<b>The system detects the bus number, verifies direction, matches saved routes, and provides intelligent alerts.</b>

# 🧠 How the System Works

# 1️⃣ Real-Time Bus Recognition
<b>Using OpenCV, OCR (Optical Character Recognition), and text filtering logic.</b>  
<b>The system detects bus numbers from the camera feed, removes irrelevant surrounding text, and generates a confidence score.</b>  
<b>Output Example: Detected Bus 534 — 92% match with saved route.</b>

# 2️⃣ Route Matching Engine
<b>Users can save frequently used routes (e.g., Home → College).</b>  
<b>The system compares the detected bus number, verifies if it serves the user’s stop, and checks travel direction.</b>  
<b>Output: Route Match Score (0–100%).</b>

# 3️⃣ Accessibility Mode (Assistive AI)
<b>Designed specifically for visually impaired users.</b>  
<b>Loud voice output.</b>  
<b>Vibration-based alerts.</b>  
<b>Large high-contrast UI.</b>  
<b>Auto-scan mode (no manual button).</b>  
<b>Earphone compatibility.</b>

# 4️⃣ Location Intelligence
<b>Using GPS integration to detect the user’s bus stop, filter buses likely to arrive there, and improve detection accuracy.</b>

# 5️⃣ Smart Notification Engine
<b>Correct bus detected – Strong vibration + voice confirmation.</b>  
<b>Other buses – Soft beep.</b>  
<b>Wrong direction – Warning voice alert.</b>  
<b>Example: “Bus 534 detected but heading opposite direction.”</b>

# 🔥 Key Features
<b>Real-time bus number detection.</b>  
<b>AI-based route matching.</b>  
<b>Confidence scoring system.</b>  
<b>Accessibility-first design.</b>  
<b>GPS-based contextual filtering.</b>  
<b>Voice + vibration alerts.</b>  
<b>Personalized saved routes.</b>

# 🏗️ System Architecture
<b>Camera Feed → OCR Detection → Text Filtering Engine → Bus Number Extraction → Route Matching System → Confidence Score → Smart Alert Engine → Voice + Vibration + UI Dashboard.</b>

# 📊 Example Workflow

<b>🚍 AI-Powered Assistive Detection Pipeline</b>


```
👤 STEP 1: User Activates Assistive Mode
      │
      ▼
📷 STEP 2: Real-Time Camera Scanning
      │
      ▼
🔎 STEP 3: OCR Text Recognition
      │
      ▼
🧠 STEP 4: AI Noise Filtering Engine
      │
      ▼
🗺️ STEP 5: Route Intelligence Matching
      │
      ▼
📊 STEP 6: Confidence Score Calculation
      │
      ▼
🔔 STEP 7: Smart Alert System Activated
      │
      ▼
🔊📳 FINAL OUTPUT: Accessible User Feedback
```

✅ Features of this version:

- Arrows `│` and `▼` clearly show flow  
- All steps aligned vertically  
- Works perfectly in **GitHub README preview**  
- No weird one-line collapsing  

---

# 🛠️ Technology Stack

# Computer Vision
<b>OpenCV.</b>  
<b>OCR Engine.</b>  

# AI & Logic
<b>Python.</b>  
<b>Text filtering algorithms.</b>  

# APIs
<b>Google Maps API.</b>  

# 🌍 Impact
<b>This system promotes independent commuting, inclusive public transportation, safer boarding experience, and accessibility-driven innovation.</b>  
<b>Target Users: Visually impaired individuals, elderly commuters, and first-time travelers.</b>

# 🏆 Innovation
<b>Detects physical-world bus boards in real-time.</b>  
<b>Matches with personalized saved routes.</b>  
<b>Provides intelligent confidence-based alerts.</b>  
<b>Designed primarily for accessibility.</b>

# 🔮 Future Scope
<b>Government bus API integration.</b>  
<b>Live bus arrival time prediction.</b>  
<b>Metro & train expansion.</b>  
<b>AR smart glasses integration.</b>  
<b>Smart city mobility integration.</b>

# ⚙️ Installation
<b>git clone https://github.com/Sagar-sain7/MOBILITY_INDEPENCE_FOR_ALL.git</b>  
<b>cd MOBILITY_INDEPENCE_FOR_ALL</b>  
<b>Open in Android Studio and run on device/emulator.</b>

# 👨‍💻 Team 
<b>UDIT DAS | SAGAR | PRIYANSHU JOSHI...</b>  
<b>B.Tech Computer Science Engineering.</b>

# ⭐ Project Status
<b>Hackathon Prototype — Under Development.</b>
