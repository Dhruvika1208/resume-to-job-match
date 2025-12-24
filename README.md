# AI Resume to Job Matcher

An AI-powered web application that analyzes a user’s resume and recommends suitable job roles based on extracted skills, education, and projects. This project is designed especially for students and freshers to understand their career fit and improve job readiness.

## Project Objective

Many students struggle to identify the right job roles that match their skills.
This project helps by reading resumes automatically, extracting relevant information, and matching skills with suitable job roles.

## What the Project Does

1. User uploads a resume in PDF format
2. Backend extracts resume text
3. Skills are identified from the resume
4. Job roles are matched based on skill overlap
5. Results are displayed on the frontend

---

## Tech Stack Used

### Frontend

* React.js
* HTML, CSS, JavaScript
* Axios for API communication

### Backend

* Python
* Flask
* Flask-CORS

### Resume Parsing

* PDFMiner

### Job Matching Logic

* Skill keyword matching
* JSON-based job role dataset

---

## Project Structure

```
resume-job-matcher/
│
├── backend/
│   ├── app.py
│   ├── resume_parser.py
│   ├── job_recommender.py
│   ├── data/
│   │   └── job_roles.json
│   ├── venv/
│   └── requirements.txt
│
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   │   └── UploadResume.jsx
│   │   ├── App.js
│   │   └── index.js
│   └── package.json
│
└── README.md
```

---

## Why Each Component Is Used

### Flask

Used to build REST APIs that handle resume upload, processing, and job recommendation logic.

### PDFMiner

Used to extract readable text from PDF resumes.

### Job Roles JSON

Stores predefined job roles and required skills. This allows easy modification and extension of job recommendations.

### React

Used to build an interactive user interface that allows resume upload and displays results.

---

## How to Run the Project

### Run Backend

```
cd backend
venv\Scripts\activate      (Windows)
source venv/bin/activate  (Mac/Linux)

flask run
```

Backend runs on
[http://127.0.0.1:5000](http://127.0.0.1:5000)

---

### Run Frontend

Open a new terminal window

```
cd frontend
npm start
```
Frontend runs on
[http://localhost:3000](http://localhost:3000)

---

## Features Implemented

* Resume upload in PDF format
* Resume text extraction
* Skill detection
* Job role recommendations
* Clean and simple UI

---

## Future Enhancements

* AI-based resume improvement suggestions
* Resume scoring system
* GPT integration for smarter recommendations
* User authentication
* Job links integration

---

## Who This Project Is For

* Students and freshers
* Tier-2 and Tier-3 college students
* Beginners in full-stack development
* Academic projects and hackathons

---

## Key Learnings

* Full-stack application development
* Frontend and backend integration
* Resume parsing techniques
* Skill-based recommendation systems
* Debugging and project structuring

---

## Author

