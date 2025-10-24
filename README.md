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
- 🌗 **Dark & Light Mode:** Toggle between themes for comfortable viewing.  
- 💥 **Workout Summary:** Displays total reps, form score, and duration after each session.  

---

## 🧩 Tech Stack

| Component | Technology Used |
|------------|----------------|
| Frontend | HTML5, CSS3, JavaScript |
| AI/Computer Vision | MediaPipe Pose (by Google) |
| Visualization | Canvas API |
| Design | Custom CSS Animations, Gradient UI |

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

🧰 Future Enhancements:

1) 🧍‍♂️ Add more exercise types (lunges, planks, yoga poses)

2) 📈 Store user progress and stats using a database

3) 🔊 Add audio feedback

4) 📱 Make it mobile-responsive

5) ☁️ Integrate cloud-based model training

**👨‍💻 Author**

**Rajas Shah**
💼 Computer Science Graduate From Pune University
📚 Passionate about AI, Fitness, and Computer Vision and Web Development.