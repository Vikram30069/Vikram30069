<div align="center">

# Vikram Banerjee

### **AI/ML Systems Engineer • Data Science • Cloud Backends**

Hyderabad, India • [Portfolio](https://sites.google.com/ds.study.iitm.ac.in/vikram-banerjee/home) • [LinkedIn](https://www.linkedin.com/in/vikram-banerjee/) • [GitHub](https://github.com/Vikram30069)

<br/>

[![Python](https://img.shields.io/badge/Python-3.11%20%7C%203.12-3776AB?style=flat-square&logo=python&logoColor=white)](https://www.python.org/)
[![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com/)
[![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)](https://pytorch.org/)
[![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)](https://www.docker.com/)
[![AWS](https://img.shields.io/badge/AWS-Cloud-FF9900?style=flat-square&logo=amazonaws&logoColor=white)](https://aws.amazon.com/)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)](https://www.postgresql.org/)

</div>

---

### 👨‍💻 Engineering Profile

I am a Computer Science and Data Science undergraduate pursuing a dual-degree track at **Matrusri Engineering College** (B.E. in Computer Science and Engineering) and the **Indian Institute of Technology, Madras (IIT Madras)** (BS in Data Science and Applications).

My engineering work focuses on **applied AI systems** and **backend engineering**:
- **Multi-Agent AI Architectures**: Deterministic agent collaboration pipelines using CrewAI, FastAPI, and structured schema validation.
- **Explainable Anomaly Detection**: Statistical behavioral models (Median / MAD baselines) for contextual financial fraud mitigation.
- **Computer Vision & Inspection**: Dual-stage defect localization combining OpenCV morphological analysis with supervised machine learning.
- **Production-Style Backends**: Layered FastAPI and PostgreSQL services with strict Pydantic v2 schemas, JWT RBAC, and containerized deployment.

---

### 🚨 Currently Building

- **[RescueNet-AI](https://github.com/Vikram30069/RescueNet-AI)**: A 10-agent autonomous disaster response orchestrator that parses distress feeds, scores survivor risk, cross-references real regional emergency asset databases, and automates multi-channel dispatches via Twilio and AWS.
- **[datadrishti (Paytm IntentGuard)](https://github.com/Vikram30069/datadrishti)**: A contextual UPI payment security layer evaluating transfers against personal behavioral baselines to intercept coercion and panic fraud without interrupting legitimate activity.

---

### 🛠️ Featured Engineering Projects

#### 1. [RescueNet-AI — 10-Agent Autonomous Disaster Response Orchestrator](https://github.com/Vikram30069/RescueNet-AI)
*Deterministic multi-agent pipeline designed to eliminate multi-agency communication bottlenecks during rapid-onset urban emergencies.*

- **System Design**: Coordinates 10 specialized CrewAI agents (Disaster Intelligence, Incident Understanding, Survivor Probability, Medical Triage, Resource Allocation, Hospital Coordination, Risk Prediction, Alert Dispatch, Command Orchestration).
- **Domain Integration**: Ingests and routes across real emergency infrastructure datasets (100+ Telangana hospitals, ambulance depots, fire stations, and NDRF battalions).
- **Backend & Cloud**: FastAPI service deployed with PostgreSQL/SQLite, Twilio API for automated SMS/Voice/WhatsApp alerts, and containerized Docker configurations.
- **Quality & Verification**: 15+ automated API and agent pipeline test suites validating triage schema contracts, agent handoffs, and resource routing.
- **Tech**: `Python 3.11` • `FastAPI` • `CrewAI` • `PostgreSQL` • `Docker` • `AWS (EC2/Bedrock)` • `Twilio API` • `Next.js 14`

```
Distress Ingestion ──▶ Incident Parser ──▶ Survivor Probability ──▶ Medical Triage
                                                                         │
Twilio Alert Dispatch ◀── Hospital Routing ◀── Resource Allocation ◀─────┘
```

---

#### 2. [datadrishti (Paytm IntentGuard) — Contextual Payment Security Layer](https://github.com/Vikram30069/datadrishti)
*Behavioral anomaly detection layer protecting UPI transfers against coercion, distress, and panic-induced financial fraud.*

- **Problem & Solution**: Standard binary fraud filters block legitimate high-value transfers (e.g. rent) while missing technically authorized transactions made under duress. IntentGuard introduces contextual personal baselines.
- **Statistical Engine**: Replaces vulnerable arithmetic averages with Median and Median Absolute Deviation (MAD) to establish personal spending thresholds.
- **Calibrated Risk Policy**: Evaluates 6 signals (Amount Anomaly, Counterparty Novelty, Time-of-Day, Device Fingerprint, Geolocation Anomaly, Velocity Surges) mapped to 4 adaptive friction states: *Allow (0–30)*, *Inform (31–55)*, *Step-Up Verification (56–80)*, and *Block (>80)*.
- **Quality & Verification**: 5 modular test suites (`test_api.py`, `test_features.py`, `test_policy.py`, `test_risk_engine.py`, `test_simulation_engine.py`).
- **Tech**: `Python` • `FastAPI` • `NumPy` • `Pandas` • `Scikit-learn` • `Docker` • `Next.js`

---

#### 3. [VisionCheck — Industrial Quality & Surface Defect Detection](https://github.com/Vikram30069/ai-image-quality-defect-detection)
*Dual-stage computer vision and machine learning inspection console for automated manufacturing surface quality assurance.*

- **Inspection Architecture**: Combines classical spatial computer vision (morphological contour analysis and thresholding) for defect localization with a trained Random Forest classifier.
- **Feature Engineering**: Extracts 7 optical quality metrics per image: sharpness index, contrast score, luminance profile, noise estimate, blur metric, edge density, and localized defect count.
- **Model Performance**: 93% classification accuracy on benchmark surface inspection samples with sub-100ms inference latency.
- **Deployment**: Production FastAPI backend, interactive visual console, and Dockerized deployment on Render with OpenAPI documentation.
- **Quality & Verification**: 25 unit/integration test cases covering image preprocessing, feature extraction pipelines, model prediction, and API endpoints.
- **Tech**: `Python 3.12` • `OpenCV` • `Scikit-Learn` • `FastAPI` • `Docker` • `Pytest`

---

#### 4. [Skynet Flight Operations API — Aviation Academy Operations Backend](https://github.com/Vikram30069/skynet-flight-ops-api)
*High-reliability REST backend enforcing aviation safety compliance, aircraft maintenance dispatch, and training sortie workflows.*

- **Domain Logic**: Implements aviation dispatch lifecycle rules, airworthiness status validation (grounded, maintenance hold, ready), and flight-hour milestone tracking.
- **Security & Authorization**: Role-Based Access Control (RBAC) with JWT tokens enforcing distinct permission scopes for Admins, Dispatchers, Chief Flight Instructors (CFI), Instructors, and Students.
- **Database Architecture**: PostgreSQL relational schema designed with SQLAlchemy ORM, clean separation of concerns (`api`, `core`, `db`, `schemas`, `services`), and database seed automation.
- **Quality & Verification**: Automated pytest suites testing aircraft readiness transitions, sortie scheduling constraints, and audit log generation.
- **Tech**: `Python 3.11` • `FastAPI` • `PostgreSQL` • `SQLAlchemy` • `Pydantic v2` • `Docker Compose` • `Pytest`

---

#### 5. [PaySphere — Intelligent Payment Simulation & Incident Dispatch](https://github.com/Vikram30069/paysphere)
*Fintech transaction processing simulation featuring explainable risk evaluation and automated emergency telephonic response.*

- **Core Capabilities**: Simulates high-value transaction processing with real-time scoring (0–100) based on transfer velocity, counterparty novelty, and anomaly thresholds.
- **Automated Incident Response**: Triggers multi-channel Twilio SMS alerts and automated synthetic voice calls for transactions exceeding risk thresholds.
- **Interface & Forensics**: 3D interactive balance overview, circular SVG risk gauge, and expandable audit drawers containing full transaction metadata and action histories.
- **Tech**: `Node.js` • `Express.js` • `JavaScript` • `Twilio API` • `HTML5/CSS3` • `Jest`

---

#### 6. [Smart Attendance System — Edge Face Recognition & Geofencing](https://github.com/Vikram30069/smart-attendance-using-face-recognition)
*Enterprise attendance platform integrating real-time computer vision, deep learning anti-spoofing, and geolocation constraints.*

- **Computer Vision Pipeline**: Real-time facial detection and 128-dimensional embedding generation using OpenCV and dlib.
- **Anti-Spoofing & Liveness**: Integrated MiniFASNet ONNX deep learning neural network for texture-based liveness verification to prevent photo, video, and screen replay attacks.
- **Institutional Controls**: Role-based web interface (Student, Teacher, Admin), automated timetable population, and GPS geofence radius validation.
- **Tech**: `Python` • `Django` • `OpenCV` • `dlib` • `MiniFASNet ONNX` • `SQLite` • `Docker`

---

### 💻 Technical Stack

<table>
  <tr>
    <td width="22%"><strong>Languages</strong></td>
    <td><code>Python</code> • <code>JavaScript</code> • <code>TypeScript</code> • <code>SQL (PostgreSQL, SQLite)</code> • <code>HTML5 / CSS3</code></td>
  </tr>
  <tr>
    <td><strong>AI & Machine Learning</strong></td>
    <td><code>PyTorch</code> • <code>Scikit-Learn</code> • <code>OpenCV</code> • <code>CrewAI (Multi-Agent)</code> • <code>LLM Orchestration</code> • <code>MiniFASNet ONNX</code> • <code>NumPy</code> • <code>Pandas</code></td>
  </tr>
  <tr>
    <td><strong>Backend & APIs</strong></td>
    <td><code>FastAPI</code> • <code>Django</code> • <code>Node.js / Express</code> • <code>Pydantic v2</code> • <code>SQLAlchemy</code> • <code>RESTful APIs</code> • <code>JWT RBAC</code></td>
  </tr>
  <tr>
    <td><strong>Data & Storage</strong></td>
    <td><code>PostgreSQL</code> • <code>SQLite</code> • <code>Redis (Basics)</code> • <code>Data Cleaning & Transformation</code></td>
  </tr>
  <tr>
    <td><strong>Cloud & DevOps</strong></td>
    <td><code>AWS (EC2, Amplify)</code> • <code>Docker</code> • <code>Docker Compose</code> • <code>GitHub Actions</code> • <code>Linux / Bash</code> • <code>Render / Vercel</code></td>
  </tr>
</table>

---

### 🔬 Engineering Principles

- **Deterministic Agent Execution**: Emergency pipelines enforce structured Pydantic input/output contracts to eliminate LLM hallucinations during life-critical dispatch operations.
- **Statistical Anomaly Baselines**: Financial security models favor non-parametric metrics (Median, Median Absolute Deviation) over vulnerable arithmetic means to prevent skew from legitimate high-value outliers.
- **Layered Backend Architecture**: Strict decoupling of routing schemas, domain service logic, database access layers, and configuration injection.
- **Automated Verification**: End-to-end unit and integration testing via `pytest` and containerized test execution in Docker before deployment.

---

### 🎓 Academic Background

- **Matrusri Engineering College** (Affiliated with Osmania University)  
  *Bachelor of Engineering (B.E.) in Computer Science and Engineering*
- **Indian Institute of Technology, Madras (IIT Madras)**  
  *Bachelor of Science (BS) in Data Science and Applications*

---

### 📬 Connect

- **LinkedIn**: [linkedin.com/in/vikram-banerjee](https://www.linkedin.com/in/vikram-banerjee/)
- **Technical Portfolio**: [Vikram Banerjee Portfolio](https://sites.google.com/ds.study.iitm.ac.in/vikram-banerjee/home)
- **GitHub**: [github.com/Vikram30069](https://github.com/Vikram30069)
