# ⚡ AI Gym Trainer 

### 🧠 Your Intelligent Fitness Companion

AI Gym Trainer is a **real-time AI-powered fitness trainer** that uses **MediaPipe Pose** and **OpenCV (via browser)** to detect your body posture through the webcam. It tracks your workout reps, evaluates your form, and provides instant feedback — helping you improve exercise technique and stay consistent.

---

## 🚀 Features

- 🎯 **Real-Time Pose Detection:** Uses MediaPipe Pose for accurate skeletal tracking.  
- 💪 **Multiple Exercises Supported:** Bicep Curls, Push-ups, Pull-ups, Sit-ups, and Squats.  
- 📊 **Form Evaluation:** Calculates joint angles and provides feedback (Good Form / Go Deeper / Keep Going).  
- 🔄 **Auto Rep Counter:** Automatically counts reps when proper movement is detected.  
- 🕒 **Workout Timer:** Tracks your session duration.  
- 📈 **Workout History Dashboard:** View complete workout history with interactive charts and analytics.
- 📊 **Progress Visualization:** Line charts showing rep progress over time and exercise distribution.
- 🏆 **Statistics Tracking:** Total workouts, favorite exercise, average form score, and best streak.
- 💾 **Data Export:** Export your workout history as CSV for external analysis.
- 🗑️ **Session Management:** Delete individual sessions or clear entire history.
- 🌗 **Dark & Light Mode:** Toggle between themes for comfortable viewing.  
- 💥 **Workout Summary:** Displays total reps, form score, and duration after each session.

---

## 🧩 Tech Stack

| Component | Technology Used |
|------------|----------------|
| Frontend | HTML5, CSS3, JavaScript |
| AI/Computer Vision | MediaPipe Pose (by Google) |
| Visualization | Canvas API, Chart.js |
| Data Storage | Browser Storage API (Persistent) |
| Design | Custom CSS Animations, Gradient UI, Glassmorphism |

---

## 📂 Project Structure
AI-GYM-Trainer/
│
├── index.html # Main project file
└── README.md # Project documentation


---

## ⚙️ How to Run Locally

1. **Clone the repository:**
   ```bash
   git clone https://github.com/RajasShah/AI-GYM-Trainer.git
2. **Navigate to the project folder:**
    cd AI-GYM-Trainer
3. **Open the project in your browser:**
    start index.html   # (Windows)
    or simply double-click on index.html.
💡 Make sure your browser allows camera access, as the trainer uses webcam input for pose detection.


🧠 How It Works:

1) Uses MediaPipe Pose to detect 33 body landmarks.

2) Calculates joint angles (e.g., shoulder–elbow–wrist for bicep curls).

3) Tracks movement stage (up/down) to determine rep completion.

4) Displays form feedback, rep count, and form score in real time.

---

## 📊 Workout History Features

The AI Gym Trainer now includes a comprehensive workout history dashboard:

### 📈 Dashboard Overview
- **Total Statistics:** View total workouts completed, total reps, favorite exercise, and average form score
- **Best Streak Tracker:** Track your longest consecutive workout streak
- **Total Time Spent:** See cumulative time spent working out

### 📉 Visual Analytics
- **Progress Chart:** Line graph showing rep count progression over your last 10 workouts
- **Exercise Distribution:** Doughnut chart displaying which exercises you perform most

### 🗂️ Session Management
- **Recent Sessions List:** View last 10 workout sessions with complete details
- **Session Details:** Date, exercise type, reps completed, duration, and form score
- **Delete Sessions:** Remove individual workout sessions
- **Clear History:** Wipe entire workout history with one click

### 💾 Data Export
- **CSV Export:** Download your complete workout history as a CSV file for analysis in Excel or Google Sheets

### 🔐 Data Persistence
All workout data is stored locally using the Browser Storage API, ensuring your privacy while maintaining your workout history across sessions.

---

## 🧰 Future Enhancements

- [ ] 🧍‍♂️ Add more exercise types (lunges, planks, yoga poses)
- [ ] 🔊 Add voice announcements for rep counts and form feedback
- [ ] 🎯 Implement goal setting and achievement badges
- [ ] 📱 Improve mobile responsiveness and touch controls
- [ ] 👥 Add social sharing of workout achievements
- [ ] 📅 Create custom workout plans and schedules
- [ ] 🌐 Multi-language support
- [ ] 🔔 Workout reminders and notifications
- [ ] ☁️ Cloud sync for cross-device data access
- [ ] 🤖 AI-powered workout recommendations based on history

**👨‍💻 Author**

**Rajas Shah**
💼 Computer Science Graduate From Pune University
📚 Passionate about AI, Fitness, and Computer Vision and Web Development.