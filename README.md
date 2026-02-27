
 🎓 VidyaMitra – AI-Powered Digital Learning & Career Assistant

VidyaMitra is a modern AI-powered web application designed to enhance digital learning and career readiness. It integrates Artificial Intelligence to provide personalized educational assistance, resume evaluation, skill mapping, career recommendations, and AI-driven mock interview simulations.

The platform is built using a scalable full-stack architecture with a React.js frontend and a FastAPI backend, ensuring performance, modularity, and future expandability.



##  Project Overview

VidyaMitra supports students, graduates, and working professionals by:

- Identifying skill gaps from resumes
- Recommending personalized courses and certifications
- Conducting AI-based mock interviews
- Providing structured career transition roadmaps
- Enhancing learning engagement through smart recommendations

The system runs frontend and backend services independently in separate terminals and uses a dedicated Python virtual environment to manage backend dependencies securely.



##  Tech Stack

### 🔹 Frontend
- React.js
- HTML5
- CSS3
- JavaScript
- Axios (API Integration)

### 🔹 Backend
- Python
- FastAPI
- Uvicorn
- Pydantic
- Token-based Authentication

### 🔹 Development Tools
- VS Code
- Git & GitHub
- Virtual Environment (venv)
- Node.js & npm



##  System Architecture

```

Client Browser
↓
React.js Frontend (Port 3000)
↓
FastAPI Backend (Port 8000)
↓
AI Processing & Data Handling

```

- Frontend handles UI and user interaction.
- Backend handles authentication, APIs, resume analysis, and AI functionalities.
- Services run independently for better scalability and modular development.

---

##  Core Features

###  1. AI Resume Evaluation
- Upload resume (PDF/Document)
- Extract and analyze skills
- Identify missing competencies
- Recommend improvement courses

###  2. Skill Mapping & Career Path Guidance
- Analyze transferable skills
- Suggest industry-relevant certifications
- Generate structured upskilling roadmap

###  3. AI Mock Interview Simulator
- Real-time interview questions
- Tone and communication analysis
- Confidence evaluation
- Personalized feedback generation

###  4. Smart Learning Recommendations
- AI-powered course filtering
- Targeted content suggestions
- Adaptive learning support

###  5. Secure Authentication
- User Registration & Login
- Token-based authentication system

---

## 🎯 Real-World Scenarios

### 🔹 Scenario 1: Personalized Resume Evaluation
A final-year engineering student uploads her resume.  
VidyaMitra identifies gaps like Data Visualization and Cloud Fundamentals and recommends relevant courses to improve employability.

### 🔹 Scenario 2: AI-Driven Mock Interview
An MBA graduate practices using the AI Interview Simulator.  
The system evaluates tone, clarity, confidence, and accuracy, providing structured feedback for improvement.

### 🔹 Scenario 3: Career Transition Planner
A working professional planning to switch to Data Science uploads his resume.  
VidyaMitra analyzes transferable skills, suggests certifications, and creates a personalized career roadmap.

---

## 📁 Project Structure

```

vidyamitra/
│
├── frontend/
│   ├── public/
│   ├── src/
│   ├── package.json
│   └── ...
│
├── backend/
│   ├── main.py
│   ├── requirements.txt
│   ├── models/
│   ├── routes/
│   └── ...
│
└── README.md

````

---

## ⚙️ Installation & Setup

### 1️⃣ Clone Repository

```bash
git clone https://github.com/your-username/vidyamitra.git
cd vidyamitra
````

---

## 🖥️ Backend Setup (FastAPI)

### Step 1: Navigate to Backend Folder

```bash
cd backend
```

### Step 2: Create Virtual Environment

#### Windows

```bash
python -m venv venv
venv\Scripts\activate
```

#### macOS

```bash
python3 -m venv venv
source venv/bin/activate
```

### Step 3: Install Dependencies

```bash
pip install -r requirements.txt
```

### Step 4: Run Backend Server

```bash
uvicorn main:app --reload
```

Backend will run at:

```
http://127.0.0.1:8000
```

---

## 🌐 Frontend Setup (React)

### Step 1: Navigate to Frontend Folder

```bash
cd frontend
```

### Step 2: Install Dependencies

```bash
npm install
```

### Step 3: Start React Application

```bash
npm start
```

Frontend will run at:

```
http://localhost:3000
```

---

##  Future Enhancements

*  Cloud Deployment (AWS / Azure / GCP)
*  Advanced Analytics Dashboard
*  Improved AI Model Integration
*  Mobile Application Version
*  Multi-language Support
*  Adaptive Learning Engine

---

##  Contribution Guidelines

1. Fork the repository
2. Create your feature branch (`git checkout -b feature-name`)
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

---

##  License

This project is licensed under the MIT License.

---




