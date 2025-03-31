# Smart India Hackathon Workshop
# Date: 26/03/2025
## Register Number: 212223110049
## Name: Sharon Steffani.F
## Problem Title
SIH 1653: Web based Selector-Applicant Simulation Software
## Problem Description
Background: Recruitment and Assessment Centre (RAC) under DRDO, Ministry of Defence carries out interviews for applications received against advertised vacancies and for promotion to next higher grade for scientific manpower inducted within DRDO. Description: The process of interviewing is a challenging task. An unbiased objective interviewing process helps identify the right talent. The basic process of an interview involves posing a set of questions by an interviewer and thereafter evaluating responses from candidates. Thus, the questions asked should be relevant and match the area/ expertise of the applicant and the responses should also be of relevance w.r.t. the question asked. Expected Solution: The proposed solution should provide experts as well as candidates a real life Board Room experience, starting with initial ice-breaking questions leading to in-depth techno-managerial (depending on the level of candidate) questions. It shall also be able to provide a quantifiable score for experts as well as the candidate for the relevancy of questions w.r.t. the area/ expertise of the applicant. Similarly, candidate responses should also be graded for relevancy w.r.t. the question asked, finally assisting in arriving at an overall score for the subject knowledge of the candidate and thus his/ her suitability against the advertised post.

## Problem Creater's Organization
Ministry of Defence

## Idea
1. Role-Based Access System
Admin Panel → Manage vacancies, interviewers, and question bank.

Interview Panel (Experts) → Select/customize questions, evaluate and rate responses.

Candidates → Participate in AI-driven, mock, or live interviews.

2. Smart Questioning System
✅ AI-Powered Question Selection

Stages: Ice-breaking → General Discussion → Techno-managerial Questions.

Adaptive Difficulty: Adjusts based on candidate performance.

Dynamic Fetching: Questions pulled from a job-specific database.

✅ Question Types:

Multiple-Choice Questions (MCQs).

Descriptive/Text-based Answers.

Scenario-based / Problem-Solving.

Behavioral Questions (HR-based).

✅ Question Relevance Matching:

NLP-based expertise analysis ensures questions match the candidate’s background.

3. AI-Powered Response Evaluation
✅ Candidate Answer Analysis

NLP & Machine Learning assess clarity, relevance, and depth.

AI checks grammar, coherence, and logical reasoning.

Experts review and rate responses for final accuracy.

✅ Scoring System

Weighted AI Score + Expert Score for fairness.

Real-time feedback to guide candidates.

✅ Live AI Feedback

AI suggests improvements in mock interviews.

Speech & sentiment analysis evaluates delivery and confidence.

4. Realistic Boardroom Experience
✅ Live & AI-Driven Interviews

Live Video Interviews (via WebRTC / Zoom API).

AI Avatar-Based Mock Interviews for practice.

Real-time Transcription & Answer Grading (Google Speech-to-Text / Whisper AI).

Emotion & Tone Analysis (IBM Watson / Google NLP) for deeper evaluation.

5. Post-Interview Analytics & Reporting
✅ Performance Reports & Insights

Detailed performance report for candidates.

Expert Questioning Analysis to ensure fairness and relevance.

Data Dashboard with insights for RAC officials.

Would you like architecture and use case diagrams based on this structure?


## Proposed Solution / Architecture Diagram

Admin Panel → Manages vacancies, interviewers, and question bank.

Interview Panel (Experts) → Selects/customizes questions, evaluates responses.

Candidates → Participate in AI-driven, mock, or live interviews.

AI-Powered Questioning System

Smart question selection (Ice-breaking → Techno-managerial).

Dynamic, job-specific questions (MCQs, descriptive, scenario-based, HR).

NLP ensures question relevance to candidate expertise.

AI-Based Response Evaluation

NLP & ML assess answer clarity, depth, and logical reasoning.

AI checks grammar, coherence; experts provide accuracy ratings.

AI + Expert weighted scoring with real-time feedback.

Realistic Boardroom Experience

Live video interviews via WebRTC/Zoom API.

AI-driven mock interviews with virtual avatars.

Real-time transcription, speech, and sentiment analysis.

Post-Interview Analytics & Reporting

Candidate performance reports (strengths, weaknesses, improvements).

Fairness analysis of expert questioning.

Data dashboards for decision-makers.

This system ensures a structured, unbiased, and AI-enhanced interview process for RAC-DRDO.

![Screenshot 2025-03-26 162058](https://github.com/user-attachments/assets/1641b709-f70f-4f72-97db-cc52c6281c0d)


## Use Cases
![Screenshot 2025-03-31 150059](https://github.com/user-attachments/assets/d464f101-1fb8-414f-a76e-9ddc211eacc0)



## Technology Stack


Frontend → React.js / Angular, WebRTC, Material-UI / Tailwind CSS

Backend → Python (Django/Flask) or Node.js (Express), REST/GraphQL APIs

AI/ML → OpenAI GPT, BERT, Google NLP, TensorFlow, Whisper AI

Database → PostgreSQL / MySQL / MongoDB, Redis (Cache)

Cloud & DevOps → AWS / GCP / Azure, Docker, Kubernetes, CI/CD Pipelines

Analytics → Power BI / Tableau / Custom Data Dashboards

## Dependencies
Dependencies
Authentication → OAuth2.0, JWT, RBAC

Speech & Sentiment Analysis → Google Speech-to-Text, IBM Watson

Logging & Monitoring → ELK Stack, Prometheus + Grafana

Security → SSL/TLS, OWASP Security Guidelines

Storage → AWS S3, Google Cloud Storage

This setup ensures an AI-driven, scalable, and secure interview system. 

