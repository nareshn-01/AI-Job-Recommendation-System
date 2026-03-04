# AI Job Recommendation System

##  Overview
The **AI Job Recommendation System** is a platform that recommends jobs to users based on the skills extracted from their resumes using Natural Language Processing (NLP).

The system analyzes user skills and compares them with job requirements to generate **personalized job recommendations**.

This project demonstrates the integration of **Java backend development, machine learning, and database systems**.

---

##  Features
- User registration and login
- Resume upload
- Skill extraction from resume
- Job listing and job search
- Job application system
- AI-based job recommendation engine
- Personalized job suggestions

---

##  Tech Stack

### Backend
- Java
- Spring Boot
- Spring Security
- REST APIs

### Machine Learning
- Python
- NLP (spaCy / NLTK)
- TF-IDF
- Cosine Similarity

### Database
- MySQL

### Frontend
- HTML
- CSS
- JavaScript (or React)

---

##  Project Structure

```
AI-Job-Recommendation-System
│
├── backend/        # Java Spring Boot backend service
├── ml-service/     # Python ML service for resume parsing and recommendations
├── frontend/       # Web user interface
├── database/       # SQL schema and database scripts
└── docs/           # Architecture diagrams and documentation
```

---

##  System Architecture

```
        Frontend (Web UI)
                │
                ▼
      Spring Boot Backend (Java)
                │
                ▼
         MySQL Database
                │
                ▼
     Python ML Recommendation Service
```

### Component Description

**Frontend**
- Provides user interface for login, resume upload, and job recommendations.

**Spring Boot Backend**
- Handles authentication
- Manages job postings and applications
- Communicates with the ML service.

**MySQL Database**
- Stores users, jobs, applications, and extracted skills.

**Python ML Service**
- Extracts skills from resumes
- Runs recommendation algorithms
- Returns ranked job results.

---

##  Installation and Setup

### Clone the Repository

```
git clone https://github.com/nareshn-01/AI-Job-Recommendation-System.git
cd AI-Job-Recommendation-System
```

---

### Backend Setup (Spring Boot)

1. Navigate to backend folder

```
cd backend
```

2. Open the project in IntelliJ IDEA or VS Code.

3. Configure database in `application.properties`

Example:

```
spring.datasource.url=jdbc:mysql://localhost:3306/job_recommendation
spring.datasource.username=root
spring.datasource.password=yourpassword
```

4. Run the Spring Boot application.

---

### ML Service Setup

Navigate to ML service folder:

```
cd ml-service
```

Install dependencies:

```
pip install flask nltk spacy scikit-learn
```

Run ML service:

```
python app.py
```

---

### Database Setup

Create database in MySQL:

```
CREATE DATABASE job_recommendation;
```

Run SQL scripts located in the `database` folder.

---

##  Future Improvements
- Advanced recommendation algorithms
- Collaborative filtering
- Real-time notifications
- Cloud deployment (AWS / GCP)
- Microservices architecture
- Docker containerization

---

##  Author
**Naresh**  
B.Tech – Artificial Intelligence & Machine Learning
