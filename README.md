# 🚍 AI-Powered Assistive Bus Recognition & Smart Mobility System
## An intelligent accessibility-focused application that helps visually impaired and elderly commuters independently identify and board the correct bus using Computer Vision, AI filtering, and smart alerts.

# 🚀 Overview
## Public transport environments are chaotic — crowded bus stops, moving vehicles, noisy surroundings, and small destination boards.
## For visually impaired and elderly commuters, identifying the correct bus often requires dependence on strangers.
## Traditional transport apps only show route schedules, do not assist during physical boarding, and do not provide real-time bus board recognition.
## This project introduces an AI-powered Assistive Mobility System that detects bus numbers in real-time and intelligently alerts users through voice, vibration, and smart route matching.

# 🎯 Problem Statement
## Daily challenges faced by visually impaired commuters include difficulty reading bus boards, risk of boarding the wrong bus, dependency on strangers, and anxiety in crowded environments.
## Existing navigation apps provide static route information, lack physical-world recognition, and do not offer accessibility-first design.

# 💡 Proposed Solution
## We developed a Hybrid Recognition + Route Intelligence Engine that combines Computer Vision, Smart Filtering, Route Matching, and Accessibility Mode.
## Instead of just scanning text: Scan → Understand → Match → Alert.
## The system detects the bus number, verifies direction, matches saved routes, and provides intelligent alerts.

# 🧠 How the System Works

# 1️⃣ Real-Time Bus Recognition
## Using OpenCV, OCR (Optical Character Recognition), and text filtering logic.
## The system detects bus numbers from the camera feed, removes irrelevant surrounding text, and generates a confidence score.
## Output Example: Detected Bus 534 — 92% match with saved route.

# 2️⃣ Route Matching Engine
## Users can save frequently used routes (e.g., Home → College).
## The system compares the detected bus number, verifies if it serves the user’s stop, and checks travel direction.
## Output: Route Match Score (0–100%).

# 3️⃣ Accessibility Mode (Assistive AI)
## Designed specifically for visually impaired users.
## Loud voice output.
## Vibration-based alerts.
## Large high-contrast UI.
## Auto-scan mode (no manual button).
## Earphone compatibility.

# 4️⃣ Location Intelligence
## Using GPS integration to detect the user’s bus stop, filter buses likely to arrive there, and improve detection accuracy.

# 5️⃣ Smart Notification Engine
## Correct bus detected – Strong vibration + voice confirmation.
## Other buses – Soft beep.
## Wrong direction – Warning voice alert.
## Example: “Bus 534 detected but heading opposite direction.”

# 🔥 Key Features
## Real-time bus number detection.
## AI-based route matching.
## Confidence scoring system.
## Accessibility-first design.
## GPS-based contextual filtering.
## Voice + vibration alerts.
## Personalized saved routes.

# 🏗️ System Architecture
## Camera Feed → OCR Detection → Text Filtering Engine → Bus Number Extraction → Route Matching System → Confidence Score → Smart Alert Engine → Voice + Vibration + UI Dashboard.

# 📊 Example Workflow

## 🚍 AI-Powered Assistive Detection Pipeline

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

Agar chaho, main isko aur **modern look with emojis + bold headers for each step** banake de sakta hoon, jo aur visually attractive lagega 😎  

Chahiye kya wo version bhi?

# 🛠️ Technology Stack

# Computer Vision
## OpenCV.
## OCR Engine.
# AI & Logic
## Python.
## Text filtering algorithms.
# APIs
## Google Maps API.

# 🌍 Impact
## This system promotes independent commuting, inclusive public transportation, safer boarding experience, and accessibility-driven innovation.
## Target Users: Visually impaired individuals, elderly commuters, and first-time travelers.

# 🏆 Innovation
## Detects physical-world bus boards in real-time.
## Matches with personalized saved routes.
## Provides intelligent confidence-based alerts.
## Designed primarily for accessibility.

# 🔮 Future Scope
## Government bus API integration.
## Live bus arrival time prediction.
## Metro & train expansion.
## AR smart glasses integration.
## Smart city mobility integration.

# ⚙️ Installation
## git clone https://github.com/Sagar-sain7/MOBILITY_INDEPENCE_FOR_ALL.git
## cd project-name
## Open in Android Studio and run on device/emulator.

# 👨‍💻 Team 
## UDIT DAS | SAGAR | PRIYANSHU JOSHI...
## B.Tech Computer Science Engineering.

# ⭐ Project Status
## Hackathon Prototype — Under Development.
