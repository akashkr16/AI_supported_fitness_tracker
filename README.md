## 💪 Fitness4Me: AI Supported Personalized Fitness Trainer Web Application 

 "Fitness4Me"  is an AI-powered personalized fitness trainer web application that integrates with
 smartwatches to provide customixxed workout routines, meal plans , and real-time health tracking. 
 It aims to bridge the gap between traditional fitness apps and intelligent, adaptive health platforms 
 by offering personalized recommendation based on user beahviour and biorhythmic patterns.


 ---


 ## 🚀 Features

 -  **Smartwatch Integration** (Google Fit, Apple HealtKit)
 -  **Biorhythm Score Analysis** using sleep, Heart rate, and step data**
 -  **Personalized workout and meal plans**
 -  **Posture Detection** via OpenCV + MediaPipe
 -  **Daily Progress Visualization**
 -  **Remainders & Notifications**
 -  **Secure local storage with SQLite3**

 ---

 ## 🛠️ Tech Stack 

**Frontend**
- HTML5
- Tailwind CSS
- JavaScript

**Backend**
- Flask (Python)

**Database**
- SQLites3

**AI & ML**
- OpenAI (GPT-based recommendation engine)
- LangChain, Vector DB for knowledge handling
- OpenCV & MediaPipe for real-time posture tracking

**Visualization**
- Matplotlib

**Design Tools**
- Figma, Adobe Illustrator

---

## System Architectecture 

- **Presentation Layer**:HTML + Tailwind CSS + JS
- **Logic Layer*: Flask (Python) - Handles API, biorythm logic, planning
- **Data Layer**: SQLite3 - Stores user profiles, logs, meals, workouts
- **Device Integration Layer**: Interface with smartwatches for real-time data

---

## Installation

### Prerequisites

- Python 3.8+
- pip (Python package installer)

### Setup 

```bash
# clone the repository
git clone https://github.com//fitness4me.git
cd fitness4me

# Create a virtual Environment (optional but recommended)
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install Dependencies
pip install -r requirements.txt

#Run the app
python app.py
