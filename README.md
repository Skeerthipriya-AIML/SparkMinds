# 🌟 SparkMinds – Learning Management System (LMS)

> **Event:** Synapse 2K25 – 24-Hour Hackathon  
> **Organized by:** Coding Club  
> **Project Title:** Learning Management System (LMS)  
> **Duration:** 24 Hours  
> **Theme:** Build and deploy a full-stack LMS with progressive functionality for students and teachers.

---

## 🧠 Challenge Overview

**SparkMinds** is an intelligent, gamified **Learning Management System (LMS)** built during **Synapse 2K25**, organized by the **Coding Club**.  
It transforms online learning through **AI-powered assistance**, **real-time grading**, and **interactive dashboards** for both students and teachers — all hosted seamlessly on **Replit**.

The project implements all levels — **Bronze → Platinum** — of the hackathon user stories, with bonus innovation through **AI integration**.

---

## 🧑‍💻 Team Information

### 🏷️ Team Name  
**SparkMinds✨**

### 👥 Team Members
- **Keerthi Priya** – Frontend Developer, UI/UX Designer, Integration Specialist.
- **KR Ganesh**- Backend & Database Engineer.
- **Krishna Priya**-Project Designer & python Developer.

---

## 🧩 Problem Statement

Traditional LMS platforms lack interactivity and personalized learning support.  
Students often face doubts that go unanswered, reducing engagement and productivity.  
**SparkMinds** bridges this gap with an **AI-driven learning assistant** and a modern, user-friendly LMS platform.

---

## 💡 Solution Overview

- ✅ **Dual dashboards** for teachers and students.  
- ✅ **Assignments and grading system** with instant performance scoring.  
- ✅ **AI-powered “Ask Guru”** chatbot for real-time doubt resolution.  
- ✅ **Responsive, modern UI** built with Tailwind CSS and React.  
- ✅ Fully deployed, integrated backend hosted on **Replit**.
- ✅ An **AI-powered Skill Path Generator** that analyzes a user’s current skills and career goals to create a personalized learning roadmap for achieving their target role efficiently.

---

## 🛠️ Tech Stack

| Layer | Technologies Used |
|--------|-------------------|
| **Frontend** | React (Vite), Tailwind CSS |
| **Backend** | Node.js, Express.js, Python Flask |
| **AI Integration** | Google Gemini API (via Flask service) |
| **Database** | MongoDB |
| **Hosting** | Replit |
| **Version Control** | GitHub |
| **Development Tools** | VS Code, npm, Git |

---

## 💬 Special Feature – “Ask Guru” (AI Chatbot)

> 🤖 **Ask Guru** is an AI-powered subject-wise assistant built with **Python Flask** and **Google Gemini API**.
> 🧭 **Skill Path Generator** is an AI-powered module recently integrated into SparkMinds.It helps learners create personalized learning paths based on their current skills, goals, and course performance.
✨ **Key Features**
-🚀 AI-Powered Recommendations: Suggests learning tracks tailored to each student’s goals.
-📊 Skill Mapping: Analyzes user progress and skill gaps using performance data.
-🧩 Dynamic Path Generation: Updates learning paths in real-time as users complete modules.
-🧠 Integration with LMS: Fully connected with the SparkMinds dashboard, allowing students and  teachers to visualize skill growth.
-💡 Automatically generates a personalized, AI-driven learning roadmap based on the user’s current skills and desired career path.


### 🔍 Description:
“Ask Guru” helps students clarify subject-related doubts instantly.  
It provides intelligent, context-aware answers to academic questions, making learning interactive and self-driven.
"Skill Path Generator"is an AI-based tool that identifies a user’s existing skills, analyzes their target career role, and generates a customized step-by-step learning roadmap with recommended courses, tools, and projects to help them reach their goals efficiently.
🔗 **How It Works**
-Students input their interests or learning goals.
-The AI engine analyzes their completed modules and quiz results.
-It generates a custom skill roadmap with recommended next steps and resources.
-The path updates automatically as the student progresses.

### ⚙️ Tech Details:
- Backend powered by **Flask** microservice.  
- Uses **Google Gemini API** for natural language understanding and response generation.  
- Integrated directly into the LMS dashboard under **Student Portal**.  
- Supports multi-subject question handling (e.g., Math, Science, Programming, etc.).
- Built using React.js for the frontend, Node.js and Express.js for the backend, MongoDB for database management, and an AI/ML engine (Python + scikit-learn/OpenAI API) for skill gap analysis and personalized roadmap generation.

### 🎯 Outcome:
Students get **personalized tutoring**, **concept explanations**, and **example-based learning** — all within the LMS environment.
Users receive a personalized, goal-oriented learning path that bridges their skill gaps, accelerates growth, and guides them step-by-step toward their desired career role.

---

## 🥇 Hackathon User Stories Completed

### 🥉 **Bronze Level (Basic)**
- ✅ User registration & login (Student/Teacher).  
- ✅ Secure authentication and role-based access.  
- ✅ Course creation and listing.

### 🥈 **Silver Level (Intermediate)**
- ✅ Course enrollment system.  
- ✅ Students can view enrolled courses.  
- ✅ Teachers can view enrolled students.

### 🥇 **Gold Level (Advanced)**
- ✅ Assignment creation and submission.  
- ✅ Teachers can review and manage submissions.  

### 💎 **Platinum Level (Expert)**
- ✅ Grading system with performance tracking.  
- ✅ **Ask Guru – AI Chatbot** for doubt clarification.  
- ✅ QuickAction section for navigation and insights.
- ✅An advanced AI mentor mode that provides expert-level personalized guidance, evaluates user progress, and suggests next-step learning strategies and real-world projects to help users master skills like an industry professional

---

## 🎨 Design & UX Highlights

- Minimal and professional interface with **Tailwind CSS**.  
- Role-based dashboards for teachers and students.  
- Consistent color palette and responsive layouts.  
- Integrated “Ask Guru” panel with chat-like interface.
- 🧭 Skill Path Generator – AI-powered feature that creates personalized learning path based      on student goals and performance.
 

---

## 🌍 Live Demo & Repository

🔗 **Hosted Link (Replit)**  
👉 [https://sparkminds-team.replit.app]

📦 **GitHub Repository**  
👉 [https://github.com/Skeerthipriya-AIML/SparkMinds]

---
SparkMinds/
├── backend/
│ ├── server.js # Express server handling APIs and database logic
│ ├── routes/ # API route definitions
│ └── models/ # Database models (Users, Courses, etc.)
├── ask-guru/
│ ├── app.py # AI module for question answering and recommendations
│ ├── requirements.txt # Python dependencies
│ └── templates/ # Web templates for AI service
├── frontend/
│ ├── src/
│ │ ├── components/ # Reusable UI components
│ │ ├── pages/ # App pages (Dashboard, Login, etc.)
│ │ └── App.jsx # Main React entry point
├── skill-path-generator/
│ ├── index.js # AI logic for personalized skill recommendations
│ ├── utils/ # Helper functions for path analysis
│ └── data/ # Skill mapping and learning resources
├── package.json # Frontend + backend dependencies
└── README.md


## ⚙️ Installation & Setup (For Local Testing)

```bash
# Clone the repository
git clone https://github.com/Skeerthipriya-AIML/SparkMinds.git

# Navigate into the project folder
cd SparkMinds

# Install dependencies
npm install

# Run the app
npm run dev


📞 Contact

**👩‍💻 Keerthi Priya**  
📧 kirtipriya032005@gmail.com  
🌐 GitHub Profile:(https://github.com/Skeerthipriya-AIML)
