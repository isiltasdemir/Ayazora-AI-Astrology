Here is the professional English version of your **README.md** for GitHub, tailored to your specific project structure and tech stack:

---

# 🌟 Ayazora - AI-Powered Astrology Application

Ayazora is a modern web application that combines artificial intelligence with real-time astronomical data to provide personalized astrological insights. By calculating precise planetary positions at the moment of birth, it generates deep psychological interpretations using the Gemini AI model.

## 🚀 Features

* **Real-time Astronomical Calculations:** Uses the `ephem` library to calculate the exact positions of the Sun, Moon, Venus, Mars, and Saturn.
* **AI-Driven Interpretations:** Leverages the Gemini 2.5 Flash model to provide unique and holistic birth chart readings.
* **Dynamic Data Flow:** Processes user inputs via a Python Flask backend and dynamically renders results on the frontend.
* **Modern UI/UX:** Features a sleek, dark-themed interface designed for an immersive user experience.

## 🛠 Tech Stack

### **Frontend**

* **HTML5 & CSS3:** Responsive design with a focus on modern aesthetics.
* **JavaScript (Vanilla):** Handles API requests, local storage, and dynamic DOM updates.

### **Backend**

* **Python (Flask):** Robust server-side logic and RESTful API architecture.
* **Flask-CORS:** Manages Cross-Origin Resource Sharing for secure communication.
* **Geopy:** Converts city names into precise geographic coordinates (Latitude/Longitude).
* **PyEphem:** Provides high-precision astronomical calculations for planetary bodies.

### **Artificial Intelligence**

* **Google Gemini API:** An advanced large language model used to synthesize and interpret planetary data into human-like insights.

### **Tools**

* **VS Code:** Primary development environment.
* **Git & GitHub:** Version control and repository management.
* **Chrome DevTools:** Used for debugging and performance monitoring.

## ⚙️ Installation & Setup

To run this project locally, follow these steps:

1. **Install required Python libraries:**
```bash
pip install flask flask-cors geopy google-genai ephem

```


2. **Configure API Key:**
Open `app.py` and replace the placeholder in `GEMINI_API_KEY` with your actual Google Gemini API key.
3. **Start the server:**
```bash
python app.py

```


4. **Launch the application:**
Open `harita.html` in your browser (preferably through a local server or a security-disabled browser session to avoid CORS issues during development).

## 📸 Screenshots

---
<img width="1869" height="855" alt="ayazora" src="https://github.com/user-attachments/assets/4c35695c-ae67-49f0-8868-71adba880135" />

