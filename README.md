
## 📌 Overview
FocusLens is built for anyone who wants to develop consistent focus habits, stay accountable, and gain insights into their productivity patterns. Whether you're studying, working, or managing personal tasks, this tool provides a simple way to track sessions, analyze performance, and build better routines over time.

The app logs focus and distraction sessions, assigns XP based on duration, tracks streaks, and displays your progress through interactive dashboards. With built-in analytics like category breakdowns, hourly patterns, and calendar heatmaps, you can easily identify when you're most productive — and what tends to pull you off track.

![XP Heatmap](XP%20Heatmap.png)

# **FocusLens**
A personal productivity tracker designed to help you monitor focus sessions, reduce distractions, and visualize your progress over time. FocusLens uses XP (experience points), streaks, and analytics to create an engaging, game-like approach to productivity — all powered by Python and Streamlit.

---


## 🛠️ Technologies Used
| Technology | Purpose |
|-----------|---------|
| **Python** | Core logic, session tracking, XP calculation |
| **Streamlit** | Web interface / front-end |
| **Matplotlib** | Data visualizations and charts |
| **Calplot** | Calendar heatmap generation |
| **JSON storage** | Lightweight local data persistence |

---

## 🚀 Features

### ⏳ Session Logging
- Track focus or distraction sessions with duration, category, and notes  
- Automatic XP calculation  
- Designed for quick, frictionless session entry  

### 🔥 Streak Tracking
- Daily streak tracker to encourage consistency  
- XP milestones (with rewards planned for future versions)

### 📊 Interactive Dashboard
- Visual summaries of your productivity  
- Hourly activity patterns  
- Category breakdowns  
- Focus vs. distraction comparisons  

### 📅 Calendar Heatmap
- View your active days across weeks and months  
- Spot productivity patterns, gaps, and streaks  

### 📝 Notes & Tags
- Add comments or reflections to any session  
- Organize your work and track your mindset  

---

## 🧩 How I Built It
1. **Data Structure & Storage**  
   I began by designing a JSON-based system to store session information, XP, streaks, and metadata. This kept development lightweight and flexible.

2. **Session Logging & XP System**  
   I implemented functions to handle session creation, XP assignment, and streak updating. The XP mechanic was inspired by leveling systems in RPGs to make productivity more engaging.

3. **Streamlit App Interface**  
   Using Streamlit, I built the UI for logging sessions, navigating pages, and viewing charts. Streamlit’s interactive widgets made it easy to iterate quickly.

4. **Visualization Layer**  
   Matplotlib and Calplot were used to generate bar charts, summaries, and calendar heatmaps that highlight productivity trends.

5. **Refinement**  
   I polished the UI layout, optimized read/write operations, cleaned up code structure, and prepared the repository for GitHub.

---

## 📚 What I Learned
Working on FocusLens taught me valuable skills, including:

- Building interactive dashboards using **Streamlit**
- Designing structured time-based data systems
- Creating clear, readable analytics with **Matplotlib**
- Generating calendar heatmaps using **Calplot**
- Managing app state and persistence without a full database
- Improving UX to support habit-building and consistent usage
- Organizing a Python project for scalability and maintainability

---

## 🔧 Future Improvements

### ✨ Feature Enhancements
- User accounts (cloud sync, multi-device support)  
- Export to CSV / Google Sheets integration  
- Session timers with audio cues  
- Weekly and monthly goal-tracking features  
- More gamification (levels, badges, achievements)

### 📈 Analytics Upgrades
- Streak history visualization  
- ML-based productivity predictions  
- Smarter productivity scoring system  

### ☁️ Infrastructure Enhancements
- Migrate JSON → SQLite or Firebase  
- Deploy online for universal access  

---

## 📦 Installation

```bash
git clone https://github.com/UsmanCh1226/FocusLens.git
cd FocusLens
pip install -r requirements.txt
streamlit run app.py


