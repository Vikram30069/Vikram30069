<div align="center">

<!-- Animated Header Banner with Glowing Waves & Gradient Title -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=1,14,24,31&height=210&section=header&text=Vikram%20Banerjee&fontSize=52&fontColor=ffffff&fontAlignY=38&desc=AI%2FML%20Systems%20Engineer%20%E2%80%A2%20Data%20Science%20%E2%80%A2%20Cloud%20Backends&descFontSize=20&descAlignY=58&descAlign=50&animation=twinkling" width="100%" alt="Vikram Banerjee - AI/ML Engineer Header" />

<!-- Animated Dynamic Typing Subtitle -->
<a href="https://github.com/Vikram30069">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=3000&pause=1200&color=60A5FA&center=true&vCenter=true&width=650&lines=Building+Deterministic+Multi-Agent+AI+Systems;Explainable+Anomaly+Detection+%26+Fintech+Security;Industrial+Computer+Vision+%26+Quality+Inspection;High-Throughput+APIs+with+FastAPI%2C+PostgreSQL+%26+AWS;CS+%40+Matrusri+%E2%80%A2+Data+Science+%40+IIT+Madras" alt="Animated Typing Subtitle" />
</a>

<p align="center">
  <a href="https://sites.google.com/ds.study.iitm.ac.in/vikram-banerjee/home"><img src="https://img.shields.io/badge/🌐_Portfolio-0D1117?style=for-the-badge&logo=googlechrome&logoColor=60A5FA" alt="Portfolio"/></a>
  <a href="https://www.linkedin.com/in/vikram-banerjee/"><img src="https://img.shields.io/badge/💼_LinkedIn-0D1117?style=for-the-badge&logo=linkedin&logoColor=0A66C2" alt="LinkedIn"/></a>
  <a href="https://chitraninstitute.com/preview/index.html"><img src="https://img.shields.io/badge/🚀_Live_Client_Platform-0D1117?style=for-the-badge&logo=vercel&logoColor=34D399" alt="Chitran Platform"/></a>
</p>

</div>

---

### ⚡ Technical Profile

I am an AI/ML and Systems Engineer pursuing a dual-degree track at **Matrusri Engineering College** (B.E. in Computer Science & Engineering) and the **Indian Institute of Technology, Madras (IIT Madras)** (BS in Data Science and Applications).

My engineering work bridges the gap between **theoretical machine learning** and **production-grade software systems**:
- 🤖 **Autonomous Multi-Agent AI**: Designing deterministic agent pipelines with structured schema boundaries, dynamic role assignment, and multi-channel telemetry.
- 🛡️ **Contextual Risk & Anomaly Engines**: Applying non-parametric statistical methods (Median / MAD baselines) to detect fraud and duress in real-time transactions.
- 👁️ **Dual-Stage Computer Vision**: Combining spatial morphological localization with supervised classifiers for automated surface inspection.
- ☁️ **High-Concurrency Cloud Backends**: Architecting asynchronous FastAPI microservices, PostgreSQL relational schemas, JWT RBAC, and Docker containers.

---

### 🚨 Currently Building

```text
┌──────────────────┬────────────────────────────────────────────────────────────────────────┐
│ Project          │ Engineering Focus & Architecture                                       │
├──────────────────┼────────────────────────────────────────────────────────────────────────┤
│ 🚨 RescueNet-AI  │ 10-Agent emergency response orchestrator (CrewAI • FastAPI • AWS)      │
│ 🛡️ datadrishti    │ Paytm IntentGuard: Behavioral UPI anomaly layer (MAD baselines • ML)   │
│ 🎨 Chitran Core  │ Production-grade client academy web platform (chitraninstitute.com)    │
└──────────────────┴────────────────────────────────────────────────────────────────────────┘
```

---

### 🛠️ Featured Engineering Projects

#### 1. [RescueNet-AI — 10-Agent Autonomous Disaster Response Orchestrator](https://github.com/Vikram30069/RescueNet-AI)
*Real-time multi-agent dispatch system designed to solve coordination failure during rapid-onset urban flooding.*

[![Status](https://img.shields.io/badge/Status-Active_Architecture-38BDF8?style=flat-square)](https://github.com/Vikram30069/RescueNet-AI)
[![Stack](https://img.shields.io/badge/Stack-Python_3.11_•_CrewAI_•_FastAPI_•_AWS_•_PostgreSQL-0D1117?style=flat-square)](https://github.com/Vikram30069/RescueNet-AI)
[![Tests](https://img.shields.io/badge/Tests-15+_Pytest_Passing-34D399?style=flat-square)](https://github.com/Vikram30069/RescueNet-AI)

```mermaid
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
```

- **Architecture**: Coordinates 10 specialized CrewAI agents governed by strict Pydantic input/output validation schemas to eliminate hallucination in emergency dispatches.
- **Regional Emergency Datasets**: Ingests and geocodes real Telangana infrastructure registries (100+ vetted hospitals, 108 ambulance depots, fire stations, and NDRF rescue battalions).
- **Automated Dispatches**: Formats and triggers real-time Twilio SMS, IVR synthetic voice calls, and Next.js live geospatial map tracking in under 45 seconds.

---

#### 2. [datadrishti (Paytm IntentGuard) — Contextual Payment Security Layer](https://github.com/Vikram30069/datadrishti)
*Behavioral anomaly detection layer protecting UPI transfers against coercion, distress, and panic-induced financial fraud.*

[![Stack](https://img.shields.io/badge/Stack-Python_•_FastAPI_•_NumPy_•_Pandas_•_Scikit--Learn-0D1117?style=flat-square)](https://github.com/Vikram30069/datadrishti)
[![Tests](https://img.shields.io/badge/Tests-5_Suites_Passing-34D399?style=flat-square)](https://github.com/Vikram30069/datadrishti)

- **The Problem**: Standard binary fraud blockers block safe high-value transfers (e.g. ₹50,000 monthly rent to a known landlord) while missing authorized transactions made under duress or panic.
- **Personal Baseline Analytics**: Evaluates transactions against personal Median and Median Absolute Deviation (MAD) distributions rather than vulnerable arithmetic averages.
- **6 Calibrated Risk Signals**: Evaluates Amount Anomaly (+30), Recipient Novelty (+20), Device Novelty (+20), Time Anomaly (+15), Geo Anomaly (+10), and Velocity Surges (+5).
- **Adaptive Friction Policies**:
  - `0–30 (Low Risk)` ➔ **ALLOW**: 1-Tap frictionless transfer.
  - `31–55 (Moderate Risk)` ➔ **INFORM**: Contextual warning banner with 1-tap review.
  - `56–80 (Elevated Risk)` ➔ **STEP-UP**: Mandatory biometric re-authentication & cooling-off delay.
  - `>80 (Severe Risk)` ➔ **BLOCK**: Transaction hold requiring out-of-band telephone clearance.

---

#### 3. [VisionCheck — Industrial Quality & Surface Defect Detection](https://github.com/Vikram30069/ai-image-quality-defect-detection)
*Dual-stage computer vision inspection engine coupling classical morphology with supervised machine learning.*

[![Live Demo](https://img.shields.io/badge/Live_Demo-Render_Console-46E3B7?style=flat-square&logo=render&logoColor=white)](https://ai-image-quality-defect-detection-ps3t.onrender.com)
[![Swagger](https://img.shields.io/badge/API_Docs-FastAPI_OpenAPI-009688?style=flat-square&logo=fastapi&logoColor=white)](https://ai-image-quality-defect-detection-ps3t.onrender.com/docs)
[![Tests](https://img.shields.io/badge/Tests-25%2F25_Passing-34D399?style=flat-square)](https://github.com/Vikram30069/ai-image-quality-defect-detection)

- **Inspection Pipeline**: Implements a dual-stage architecture: classical spatial morphology (Sobel/Otsu contour localization) identifies physical defect boundaries, while a trained **Random Forest Classifier (93% accuracy)** evaluates 7 optical features (sharpness index, contrast, luminance, noise estimate, blur metric, edge density, and defect count).
- **Production Deployment**: Containerized in Docker, deployed on Render with an interactive inspection console and sub-100ms inference API endpoints.

---

#### 4. [Skynet Flight Operations API — Aviation Academy SaaS Backend](https://github.com/Vikram30069/skynet-flight-ops-api)
*High-reliability REST backend enforcing aviation safety compliance, aircraft maintenance dispatch, and training sortie workflows.*

[![Stack](https://img.shields.io/badge/Stack-FastAPI_•_PostgreSQL_15_•_SQLAlchemy_•_Pydantic_v2-0D1117?style=flat-square)](https://github.com/Vikram30069/skynet-flight-ops-api)
[![Docker](https://img.shields.io/badge/Docker-Compose_Ready-2496ED?style=flat-square&logo=docker&logoColor=white)](https://github.com/Vikram30069/skynet-flight-ops-api)

- **Domain Compliance**: Implements civil aviation sortie authorization workflows, validating student flight syllabus prerequisites, instructor endorsements, and aircraft airworthiness states (`AIRWORTHY`, `MAINTENANCE_HOLD`, `GROUNDED`).
- **Security & Database**: Role-Based Access Control (RBAC) with JWT tokens enforcing permission scopes across 5 user tiers (Admin, Dispatcher, CFI, Instructor, Student) with an automated PostgreSQL seed pipeline.

---

#### 5. [PaySphere — Intelligent Payment Simulation & Incident Dispatch](https://github.com/Vikram30069/paysphere)
*Fintech transaction processing simulation featuring explainable risk evaluation and automated emergency telephonic response.*

[![Stack](https://img.shields.io/badge/Stack-Node.js_•_Express_•_Twilio_SMS_%26_Voice_•_CSS3D-0D1117?style=flat-square)](https://github.com/Vikram30069/paysphere)

- **Automated Incident Response**: Triggers real-time Twilio SMS verification codes and programmable voice IVR phone calls when a simulated payment exceeds critical anomaly thresholds.
- **Interactive Security UI**: Features an interactive 3D holographic balance card with mouse-tracking tilt, circular SVG risk gauge (0–100), and transaction forensic audit drawers.

---

#### 6. [Smart Attendance & Liveness Verification System](https://github.com/Vikram30069/smart-attendance-using-face-recognition)
*Enterprise attendance platform integrating real-time computer vision, deep learning anti-spoofing, and geolocation constraints.*

[![Stack](https://img.shields.io/badge/Stack-Django_•_OpenCV_•_dlib_•_MiniFASNet_ONNX_•_Docker-0D1117?style=flat-square)](https://github.com/Vikram30069/smart-attendance-using-face-recognition)

- **Edge Deep Learning**: Defends against 2D printed photographs, video screens, and mask replays using a **MiniFASNet ONNX neural network** for real-time texture liveness detection.
- **Institutional Governance**: Combines facial landmark matching with browser GPS geofence radius checks, automated timetable seeding, and role-based student/faculty dashboards.

---

### 💻 Technical Stack & Tooling

<div align="center">

<!-- Sleek Dark Themed Icon Badges -->
<a href="https://skillicons.dev">
  <img src="https://skillicons.dev/icons?i=python,pytorch,tensorflow,fastapi,django,nodejs,express,postgres,sqlite,redis,docker,aws,linux,git,githubactions,nextjs,ts,js,tailwind,html,css" alt="Tech Stack Icons" />
</a>

</div>

<br/>

<table>
  <tr>
    <td width="24%"><strong>AI & Machine Learning</strong></td>
    <td><code>PyTorch</code> • <code>TensorFlow</code> • <code>Scikit-Learn</code> • <code>OpenCV</code> • <code>CrewAI (Multi-Agent)</code> • <code>LLM Orchestration</code> • <code>MiniFASNet ONNX</code> • <code>NumPy</code> • <code>Pandas</code></td>
  </tr>
  <tr>
    <td><strong>Backend & Systems</strong></td>
    <td><code>Python (3.11/3.12)</code> • <code>FastAPI</code> • <code>Django</code> • <code>Node.js / Express</code> • <code>Pydantic v2</code> • <code>SQLAlchemy</code> • <code>JWT RBAC</code> • <code>RESTful APIs</code></td>
  </tr>
  <tr>
    <td><strong>Data & Persistence</strong></td>
    <td><code>PostgreSQL</code> • <code>SQLite</code> • <code>Redis (Basics)</code> • <code>Data Cleaning & ETL</code> • <code>PySpark (Foundations)</code></td>
  </tr>
  <tr>
    <td><strong>Cloud & Infrastructure</strong></td>
    <td><code>AWS (EC2, Bedrock, Amplify)</code> • <code>Docker</code> • <code>Docker Compose</code> • <code>GitHub Actions (CI/CD)</code> • <code>Linux / Bash</code> • <code>Render / Vercel</code></td>
  </tr>
  <tr>
    <td><strong>Web & Client Systems</strong></td>
    <td><code>Next.js 14/15</code> • <code>TypeScript</code> • <code>JavaScript</code> • <code>Tailwind CSS</code> • <code>Production Platform Engineering</code></td>
  </tr>
</table>

---

### 📊 GitHub Activity & Metrics

<div align="center">

<img src="https://streak-stats.demolab.com/?user=Vikram30069&theme=tokyonight&hide_border=true&background=0D1117&ring=60A5FA&fire=38BDF8&currStreakNum=ffffff&sideNums=ffffff&currStreakLabel=60A5FA" alt="GitHub Streak" height="175" />

</div>

---

### 🎓 Academic Background

- **Matrusri Engineering College** (Affiliated with Osmania University)  
  *Bachelor of Engineering (B.E.) in Computer Science and Engineering*
- **Indian Institute of Technology, Madras (IIT Madras)**  
  *Bachelor of Science (BS) in Data Science and Applications*

---

<div align="center">

<!-- Animated Wave Footer -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=1,14,24,31&height=120&section=footer" width="100%" alt="Footer Wave" />

<p>
  <strong>Vikram Banerjee</strong> • <a href="https://sites.google.com/ds.study.iitm.ac.in/vikram-banerjee/home">Portfolio</a> • <a href="https://www.linkedin.com/in/vikram-banerjee/">LinkedIn</a> • <a href="https://github.com/Vikram30069">GitHub</a>
</p>

</div>
