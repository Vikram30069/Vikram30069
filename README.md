<div align="center">

<!-- 3D Animated Hero Banner -->

<img src="https://raw.githubusercontent.com/Vikram30069/Vikram30069/main/banner.svg" width="100%" alt="Vikram Banerjee - 3D Animated Banner" />

<br/>

<!-- Dynamic Animated Terminal Status -->

<a href="https://vikram30069.github.io/"> <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=19&duration=3000&pause=1200&color=60A5FA&center=true&vCenter=true&width=750&lines=BS+Data+Science+%40+IIT+Madras+%E2%80%A2+AI%2FML+%26+Systems+Builder;Building+Deterministic+Multi-Agent+AI+Systems;City+Operations+Head+%40+Boundless+IIT+Madras;Project+Executive+%26+Facilitator+%40+Bajaj+Foundation;Certified+Musician+(8th+Grade+IFAA)+%26+Music+Educator;Seeking+AI%2C+Data+Science+%26+Software+Internships" alt="Animated Typing Subtitle" /> </a>

<p align="center"> <a href="https://vikram30069.github.io/"> <img src="https://img.shields.io/badge/🌐_Portfolio-0D1117?style=for-the-badge&logo=googlechrome&logoColor=60A5FA" alt="Portfolio"/> </a> <a href="https://www.linkedin.com/in/vikram-banerjee/"> <img src="https://img.shields.io/badge/💼_LinkedIn-0D1117?style=for-the-badge&logo=linkedin&logoColor=0A66C2" alt="LinkedIn"/> </a> <a href="https://chitraninstitute.com/preview/index.html"> <img src="https://img.shields.io/badge/🎨_Chitran_Institute-0D1117?style=for-the-badge&logo=vercel&logoColor=34D399" alt="Chitran Platform"/> </a> </p>

</div>

👨‍💻 About Me

Dual-degree Computer Science & Data Science undergraduate building deterministic multi-agent AI systems, contextual anomaly detection pipelines, and fault-tolerant backend microservices.

Currently pursuing:

🎓 BS in Data Science and Applications at the Indian Institute of Technology, Madras (IIT Madras)
🎓 Undergraduate in Computer Science & Engineering (Class of 2027)

Leadership & Operations:

🏢 City Operations Head @ Boundless (IIT Madras)
🏢 Project Executive & Facilitator @ Bajaj Foundation (driving partner deals, budget optimization, and project execution across Telangana)
🎓 Ex-Intern @ IIIT Hyderabad (IIIT-H)

Beyond Code:

🎹 8th Grade Certified Musician & Educator (Indian Fine Arts Association, Visva-Bharati University) with 4+ years of teaching experience mentoring 100+ students across Keyboard, Tabla, Jazz Drums, Harmonium, Octapad, Violin, and Dholak.
🚨 What I'm Building & Leading
text
┌──────────────────┬────────────────────────────────────────────────────────────────────────┐
│ Area             │ Focus & Real-World Impact                                              │
├──────────────────┼────────────────────────────────────────────────────────────────────────┤
│ 🚨 RescueNet-AI  │ 10-Agent emergency response orchestrator (CrewAI • FastAPI • AWS)      │
│ 🛡️ datadrishti    │ Paytm IntentGuard: Behavioral UPI anomaly layer (MAD baselines • ML)   │
│ 🏢 Bajaj Fdn     │ Project Executive: Deal negotiation, budget optimization & analytics   │
│ 🎨 Chitran Core  │ Web platform engineering (chitraninstitute.com) & Music Faculty        │
└──────────────────┴────────────────────────────────────────────────────────────────────────┘

🛠️ Featured Engineering Projects
1. RescueNet-AI — 10-Agent Autonomous Disaster Response Orchestrator

Deterministic multi-agent pipeline designed to eliminate multi-agency communication bottlenecks during rapid-onset urban flooding.

![Stack](https://img.shields.io/badge/Stack-Python_3.11_•_CrewAI_•_FastAPI_•_AWS_•_PostgreSQL-0D1117?style=flat-square) ![Tests](https://img.shields.io/badge/Tests-15%2B_Pytest_Passing-34D399?style=flat-square)

mermaid
graph LR
    CALLS[Raw Distress Ingestion] --> A1[1. Incident Understanding]
    A1 --> A2[2. Disaster Intelligence]
    A2 --> A3[3. Survivor Probability]
    A3 --> A4[4. Medical Triage]
    A4 --> A5[5. Priority Scoring]
    A5 --> A6[6. Resource Allocation]
    A6 --> A7[7. Hospital Coordination]
    A7 --> A8[8. Risk Prediction]
    A8 --> A9[9. Twilio Alerts]
    A9 --> A10[10. Master Rescue Plan]

Architecture: Coordinates 10 specialized CrewAI agents governed by strict Pydantic input/output schemas to reduce hallucinations in emergency dispatches.
Regional Emergency Datasets: Ingests and geocodes Telangana infrastructure registries, including hospitals, ambulance depots, fire stations, and NDRF rescue battalions.
Automated Dispatches: Integrates Twilio SMS, IVR synthetic voice calls, and Next.js live geospatial map tracking.
2. datadrishti (Paytm IntentGuard) — Contextual Payment Security Layer

Behavioral anomaly detection layer designed to identify potentially coercive, distressed, or panic-induced UPI transfers.

![Stack](https://img.shields.io/badge/Stack-Python_•_FastAPI_•_NumPy_•_Pandas_•_Scikit--Learn-0D1117?style=flat-square) ![Tests](https://img.shields.io/badge/Tests-5_Suites_Passing-34D399?style=flat-square)

The Problem: Traditional fraud detection can block legitimate high-value transfers while missing authorized transactions made under coercion or panic.
Personal Baseline Analytics: Evaluates transactions using personal Median and Median Absolute Deviation (MAD) baselines instead of relying only on arithmetic averages.
6 Calibrated Risk Signals: Amount Anomaly (+30), Recipient Novelty (+20), Device Novelty (+20), Time Anomaly (+15), Geo Anomaly (+10), and Velocity Surges (+5).
Adaptive Friction Policies: Uses risk scores to determine whether a transfer proceeds normally, requires additional authentication, or needs out-of-band verification.
3. VisionCheck — Industrial Quality & Surface Defect Detection

Dual-stage computer vision inspection engine combining classical image processing with supervised machine learning.

![Live Demo](https://img.shields.io/badge/Live_Demo-Render_Console-46E3B7?style=flat-square&logo=render&logoColor=white) ![Swagger](https://img.shields.io/badge/API_Docs-FastAPI_OpenAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Tests](https://img.shields.io/badge/Tests-25%2F25_Passing-34D399?style=flat-square)

Inspection Pipeline: Uses Sobel edge detection and Otsu thresholding for defect localization, followed by a Random Forest classifier evaluating seven optical features.
Model Performance: Reports 93% classification accuracy, based on the project's evaluation.
Production Deployment: Dockerized application deployed on Render with an interactive inspection console and FastAPI endpoints.
4. Skynet Flight Operations API — Aviation Academy SaaS Backend

REST backend designed to manage aviation safety compliance, aircraft maintenance, and training sortie workflows.

![Stack](https://img.shields.io/badge/Stack-FastAPI_•_PostgreSQL_15_•_SQLAlchemy_•_Pydantic_v2-0D1117?style=flat-square) ![Docker](https://img.shields.io/badge/Docker-Compose_Ready-2496ED?style=flat-square&logo=docker&logoColor=white)

Domain Compliance: Implements flight authorization workflows that validate student syllabus prerequisites, instructor endorsements, and aircraft airworthiness states (AIRWORTHY, MAINTENANCE_HOLD, GROUNDED).
Security & Database: Implements role-based access control (RBAC) with JWT tokens, five user tiers, and a PostgreSQL seed pipeline
