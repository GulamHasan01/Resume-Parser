# AI ATS Resume Screening System

An AI-powered ATS (Applicant Tracking System) Resume Screening platform built using Java, Spring Boot, MongoDB, Azure Blob Storage, and Groq AI.

The system allows candidates to upload resumes in PDF format, automatically extracts and analyzes resume content, generates ATS scores, evaluates role compatibility, identifies strengths and weaknesses, and provides AI-based improvement suggestions. HR users can rank, filter, and compare candidates using intelligent hiring insights.

---

## 🚀 Features

* Resume PDF Upload
* AI-Based Resume Parsing
* ATS Score & Category Generation
* Role Match Percentage Calculation
* Technical & Soft Skill Extraction
* Candidate Ranking System
* Skill-Based Candidate Filtering
* Multi-Candidate Comparison
* Async Resume Processing
* Azure Blob Storage Integration
* REST API Architecture

---

## 🛠 Tech Stack

### Backend

* Java
* Spring Boot
* Spring Data MongoDB
* Maven

### Cloud & AI

* Microsoft Azure Blob Storage
* Groq API (Llama 3.3 70B)

### Database

* MongoDB

### Libraries & Tools

* Apache PDFBox
* Jackson ObjectMapper
* Async Processing

---

## 📂 Project Structure

```bash
Resume-Parser/
│
├── backend/
│   ├── controller/
│   ├── service/
│   ├── repository/
│   ├── model/
│   └── config/
│
├── frontend/
│
├── README.md
└── .gitignore
```

---

## ⚡ API Features

### Candidate APIs

* Upload Resume
* Get ATS Analysis
* View Resume Insights

### HR APIs

* Rank Candidates
* Filter by Skills
* Compare Candidates

---

## 🧠 AI Analysis Includes

* ATS Score
* Resume Summary
* Technical Skills
* Soft Skills
* Recommended Roles
* Missing Skills
* Strengths & Weaknesses
* Learning Suggestions
* ATS Keywords

---

## ☁️ Azure Integration

Uploaded resumes are stored securely in Azure Blob Storage with metadata tracking support.

---

## 🔥 Future Improvements

* Job Description Matching
* AI Interview Question Generator
* Recruiter Dashboard Analytics
* Resume Similarity Detection
* Email Notifications
* Authentication & Authorization

---

## ▶️ Run Locally

### Clone Repository

```bash
git clone https://github.com/GulamHasan01/Resume-Parser.git
```

### Configure Environment Variables

```properties
GROQ_API_KEY=your_api_key
MONGO_URI=your_mongodb_uri
AZURE_STORAGE_CONNECTION_STRING=your_connection_string
```

### Run Backend

```bash
mvn spring-boot:run
```

---

## 📌 Use Cases

* Smart Resume Screening
* AI-Based Recruitment Assistance
* ATS Resume Analysis
* Candidate Skill Evaluation
* Hiring Automation

---

## 👨‍💻 Author

Gulam Hasan

* GitHub: https://github.com/GulamHasan01
* LinkedIn: https://linkedin.com/in/gulam-hasan-80751a330

---
