The Explainability in AI-Based Online Exam Proctoring System is a secure and intelligent web application designed to enhance transparency, fairness, and accountability in digital examinations.

Unlike traditional online proctoring tools that merely flag suspicious activities without justification, this system integrates Explainable AI (XAI) principles to generate clear, timestamped violation logs with supporting visual evidence. This ensures that every flagged action is interpretable, traceable, and supported by concrete data.

The system promotes trust between students and educators by combining real-time AI monitoring with structured reporting mechanisms.

🎯 Objectives

Detect suspicious behaviors in real time using AI and computer vision

Generate interpretable and timestamped violation reports

Provide visual evidence for flagged activities

Enable real-time alerts and monitoring

Ensure fairness, accountability, and transparency in online assessments

🚀 Key Features

Secure JWT-based Authentication

Teacher Dashboard (Exam Creation & Monitoring)

Student Dashboard (Exam Participation Interface)

Real-Time AI Camera Monitoring

Browser Activity Violation Detection

Timestamped Exam Logs with Explainable Reports

Real-Time Alerts System

Result Processing and Management

🛠️ Technology Stack
Frontend

React.js

Redux Toolkit

TensorFlow.js

Material-UI

React Router

Backend

Node.js

Express.js

MongoDB

Mongoose

JSON Web Tokens (JWT)

Bcrypt.js

🏗️ System Architecture

The system consists of:

Frontend Interface – Student and Teacher portals

AI Monitoring Module – Webcam and browser activity tracking

Backend Server – Authentication, logging, and data processing

Database Layer – Secure storage of exam data and violation logs

All violations are recorded with:

Timestamp

Type of violation

Supporting evidence

Interpretable explanation

⚙️ Installation & Setup
1. Clone the Repository
git clone https://github.com/your-username/your-repository-name.git
cd your-repository-name

2. Backend Setup
cd backend
npm install
npm start

3. Frontend Setup
cd frontend
npm install
npm start

🔐 Environment Configuration

Create a .env file in the backend directory:

PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key


Ensure MongoDB is running locally or provide a cloud connection string.

📊 Impact

This system enhances:

Transparency in AI decision-making

Fairness in student evaluation

Integrity in online examinations

Trust between stakeholders in digital education

🔮 Future Enhancements

Advanced gaze tracking mechanisms

Multi-face detection improvements

Cloud-based scalable deployment

Integration with Learning Management Systems (LMS)
