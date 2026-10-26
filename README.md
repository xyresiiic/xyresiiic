<h1 align="center">Veer Pratap Singh</h1>
<p align="center"><i>Cybersecurity Enthusiast · Full‑Stack Developer · AI Builder</i></p>

```bash
$ whoami
Veer Pratap Singh — B.Tech CSE (3rd Year), Arya College of Engineering, Jaipur

$ cat focus.txt
Cybersecurity | Full-Stack Development | Applied AI

$ echo $MOTTO
"Build systems. Break assumptions. Secure everything."
```

<p align="center">
  <a href="mailto:xyresiiic@gmail.com"><img src="https://img.shields.io/badge/Email-4F46E5?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://linkedin.com/in/veer-pratap-singh-77702b316"><img src="https://img.shields.io/badge/LinkedIn-4F46E5?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://github.com/xyresiiic"><img src="https://img.shields.io/badge/GitHub-4F46E5?style=flat-square&logo=github&logoColor=white" alt="GitHub"></a>
  <a href="https://os-portfolio-xyresiiic.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-4F46E5?style=flat-square&logo=vercel&logoColor=white" alt="Portfolio"></a>
  <a href="https://instagram.com/ivee.rrr"><img src="https://img.shields.io/badge/Instagram-4F46E5?style=flat-square&logo=instagram&logoColor=white" alt="Instagram"></a>
</p>

<br>

## 🧑‍💻 About

3rd-year CSE student who likes taking things apart to see how they break — then building them back sturdier. Currently splitting time between full-stack web development, applied AI, and the fundamentals of cybersecurity, with a creative practice in photography and design on the side.

- 🔐 Aspiring cybersecurity engineer, currently deepening networking and web-security fundamentals
- 🧠 Building AI-assisted tools — from multimodal triage systems to conservation platforms
- 🚀 Four internships, five hackathons and a habit of shipping real, working projects
- 📸 Photographer and designer when I'm away from the keyboard

<br>

## 🧰 Tech Stack

**Languages**
<br>
<img src="https://skillicons.dev/icons?i=c,cpp,java&theme=dark" alt="C, C++, Java" height="48">

**Web Development**
<br>
<img src="https://skillicons.dev/icons?i=html,css,js&theme=dark" alt="HTML, CSS, JavaScript" height="48">

**Systems, Tools & Data**
<br>
<img src="https://skillicons.dev/icons?i=linux,git,github," alt="Linux, Git, GitHub," height="48">

**Security Fundamentals**
<br>
<img src="https://img.shields.io/badge/Networking-1E293B?style=flat-square" alt="Networking">
<img src="https://img.shields.io/badge/Web%20Application%20Security-1E293B?style=flat-square" alt="Web Application Security">
<img src="https://img.shields.io/badge/SQL%20Injection%20%26%20Vulnerability%20Analysis-1E293B?style=flat-square" alt="SQLi & Vulnerability Analysis">

<br>

## 📊 Skill Proficiency

| Area | Level |
|:--|:--:|
| C / C++ | ![Advanced](https://img.shields.io/badge/Advanced-10B981?style=flat-square) |
| Web Development | ![Proficient](https://img.shields.io/badge/Proficient-4F46E5?style=flat-square) |
| Java | ![Proficient](https://img.shields.io/badge/Proficient-4F46E5?style=flat-square) |
| Problem Solving | ![Proficient](https://img.shields.io/badge/Proficient-4F46E5?style=flat-square) |
| Cyber Security | ![Learning](https://img.shields.io/badge/Learning-F59E0B?style=flat-square) |

<p align="center"><br>
<img src="https://img.shields.io/badge/Web%20Development-4F46E5?style=flat-square" alt="Web Development"> →
<img src="https://img.shields.io/badge/AI-4F46E5?style=flat-square" alt="AI"> →
<img src="https://img.shields.io/badge/Cyber%20Security-4F46E5?style=flat-square" alt="Cyber Security">
<br><sub>Build applications → make them intelligent → make them secure</sub>
</p>

<br>

## 🚀 Featured Projects

### 🏫 CampusPass
*Smart Campus Attendance System — SKIT College Hackathon Project*

A mobile-first attendance management system that combines face verification and GPS geofencing to help college staff mark attendance directly from their phones, reducing queues and congestion at the campus gate.

```mermaid
flowchart LR
    A["📱 Staff Login"] --> B["📸 Live Camera Capture"]
    B --> C["🧑 Face Verification"]
    C --> D{"📍 Location Check"}
    D -->|Inside Campus| E["✅ Attendance Check-in/out"]
    D -->|Outside Campus| F["❌ Access Denied"]
    E --> G["🖥️ Admin Dashboard"]
    G --> H["📊 Attendance Records"]
```

- Secure staff login and attendance check-in/check-out
- Live camera-based face verification for staff identity
- GPS geofencing to restrict attendance to the approved campus area
- Admin dashboard for monitoring staff attendance and reviewing records
- React frontend with a FastAPI backend and database integration

**Tech Stack**

<img src="https://img.shields.io/badge/React-1E293B?style=flat-square&logo=react&logoColor=61DAFB" alt="React">
<img src="https://img.shields.io/badge/TypeScript-1E293B?style=flat-square&logo=typescript&logoColor=3178C6" alt="TypeScript">
<img src="https://img.shields.io/badge/FastAPI-1E293B?style=flat-square&logo=fastapi&logoColor=009688" alt="FastAPI">
<img src="https://img.shields.io/badge/Python-1E293B?style=flat-square&logo=python&logoColor=3776AB" alt="Python">
<img src="https://img.shields.io/badge/PostgreSQL-1E293B?style=flat-square&logo=postgresql&logoColor=4169E1" alt="PostgreSQL">
<img src="https://img.shields.io/badge/Vercel-1E293B?style=flat-square&logo=vercel&logoColor=white" alt="Vercel">
<img src="https://img.shields.io/badge/Render-1E293B?style=flat-square&logo=render&logoColor=white" alt="Render">

<a href="https://github.com/xyresiiic/CampusPass-IGNITE"><img src="https://img.shields.io/badge/View%20Repository-4F46E5?style=flat-square&logo=github&logoColor=white" alt="View Repository"></a>

**Project Status:** 🚀 Completed Hackathon Project | Built for SKIT College

<br>

### 🚑 AI Triage Pro
*Multimodal emergency dispatch system — 🏆 4th Place, HackNexus 2.0*

Combines speech and vision models to analyze emergency situations and generate intelligent triage recommendations in real time.

```mermaid
flowchart LR
    A["🎙️ Emergency Audio"] --> B["Whisper Transcription"]
    C["🖼️ Injury Image"] --> D["CLIP Vision Analysis"]
    B --> E{"Fusion Engine"}
    D --> E
    E --> F["Severity Score"]
    F --> G["🚑 Dispatch Recommendation"]
```

- Emergency call transcription via Whisper
- Injury image analysis via CLIP
- Weighted multimodal fusion for severity scoring and dispatch recommendations

<img src="https://img.shields.io/badge/Python-1E293B?style=flat-square" alt="Python">
<img src="https://img.shields.io/badge/Flask-1E293B?style=flat-square" alt="Flask">
<img src="https://img.shields.io/badge/Whisper-1E293B?style=flat-square" alt="Whisper">
<img src="https://img.shields.io/badge/CLIP-1E293B?style=flat-square" alt="CLIP">
<img src="https://img.shields.io/badge/Transformers-1E293B?style=flat-square" alt="Transformers">

<a href="https://github.com/xyresiiic/AI-TRIAGE-PRO-Project-"><img src="https://img.shields.io/badge/View%20Repository-4F46E5?style=flat-square&logo=github&logoColor=white" alt="View Repository"></a>


### 🛰️ WildLink AI
*AI-powered wildlife habitat connectivity & conservation platform*

A conservation-intelligence platform that identifies critical habitat corridors, prioritizes restoration areas, and simulates conservation interventions using GIS and graph-based analysis.

```mermaid
flowchart LR
    A["🗺️ Geospatial Data"] --> B["🌍 Habitat Suitability Analysis"]
    B --> C["🔗 Corridor & Connectivity Graph"]
    C --> D["🔄 What-If Restoration Simulation"]
    D --> E["🎯 Prioritization Score"]
```

- Interactive GIS-based habitat visualization with corridor analysis
- Graph-based connectivity modeling between habitat patches
- AI/ML-assisted spatial analysis and restoration simulation

<img src="https://img.shields.io/badge/Python-1E293B?style=flat-square" alt="Python">
<img src="https://img.shields.io/badge/PostGIS-1E293B?style=flat-square" alt="PostGIS">
<img src="https://img.shields.io/badge/Leaflet-1E293B?style=flat-square" alt="Leaflet">
<img src="https://img.shields.io/badge/Docker-1E293B?style=flat-square" alt="Docker">

<a href="https://github.com/xyresiiic/WildLifeAI"><img src="https://img.shields.io/badge/View%20Repository-4F46E5?style=flat-square&logo=github&logoColor=white" alt="View Repository"></a>

<br>

## 💻 Other Projects

| Project | Description | Link |
|:--|:--|:--:|
| 🌐 Personal Portfolio | Modern animated portfolio showcasing projects and creative work | [Visit ↗](https://portfolio-xyresiiic.vercel.app/) |
| 🖥️ Retro OS Portfolio | Retro, OS-themed animated portfolio (vibe-coded) | [Visit ↗](https://os-portfolio-xyresiiic.vercel.app/) |
| 📅 Content Calendar | Smart content scheduling & planning tool for creators and brands | [Visit ↗](https://xyresiiic.github.io/Content-Calandar/) |
| 💎 Lustréva | Luxury gifting concept site — elegant UI and branding | [Visit ↗](https://xyresiiic.github.io/Landinge-page/) |
| 🩺 MedicSoul | Healthcare assistant concept with chatbot-based interaction | [Visit ↗](https://xyresiiic.github.io/madicSoul/) |
| 🧮 Basic Calculator | Responsive calculator built to practice frontend fundamentals | [Visit ↗](https://xyresiiic.github.io/Basic_calculator/) |
| 🧑‍💻 CodSoft Projects | Calculator · To-Do List · Number Guessing Game | [Repo ↗](https://github.com/xyresiiic/CODSOFT) |

<br>

## 🏆 Achievements

| Achievement | Details |
|:--|:--|
| 🥇 HackNexus 2.0 | 4th Place — AI Triage Pro |
| 🔐 Cyber Security Internship | Triple One Solution — 2 months |
| 💻 Web Development Internship | IBM |
| 🌐 Web Dev + C++ Internship | CodSoft |
| 🧑‍💻 C++ Internship | CodeAlpha |

<br>

## 💼 Experience

| Role | Organization | Duration |
|:--|:--|:--:|
| Cyber Security Intern | Triple One Solution | 2 months |
| Web Development Intern | CodSoft | 1 months |
| C++ Intern | CodeAlpha | 1 months |

**Triple One Solution** — Practical exposure to cybersecurity concepts, security fundamentals, vulnerability analysis, and secure systems.
**CodSoft** — Practical programming and frontend development: Calculator, To-Do List, Number Guessing Game.
**CodeAlpha** — Core C++ programming concepts and applied development tasks.

<br>

## 📜 Certifications

| Certification | Issuer |
|:--|:--|
| Basics of Quadcopter | IIT Roorkee |
| Blockchain Technology | IIT Roorkee |
| Web Development Fundamentals | IBM |
| Virtual Tech Internship | Deloitte |
| Software Engineering Simulation | Accenture |
| Solution Architecture Simulation | AWS |
| GenAI Data Analytics Simulation | Tata |
| Prompt Design in Vertex AI | Google |
| Building Real-World AI Applications with Gemini & Imagen | Google |
| Web Development Internship | CodSoft |
| C++ Internship | CodeAlpha |

<br>

## 📊 GitHub Analytics

<br><br>
<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=xyresiiic&bg_color=00000000&color=00bfff&line=00bfff&point=ffffff&area=true&hide_border=true" width="95%" />

</div><br><br><br>


<div align="center">

<img src="https://streak-stats.demolab.com?user=xyresiiic&theme=transparent&hide_border=true&fire=TRUE&currStreakLabel=00BFFF&sideLabels=FFFFFF&currStreakNum=FFFFFF&sideNums=FFFFFF" width="70%" />

</div><br><br>

## 📸 Beyond Code

Photography, videography, and graphic design fill the time I'm not writing code — the same eye for composition and detail carries over into how I approach interfaces and products. Tools of choice: Photoshop, Lightroom, Canva, and VN.

<br>

## 🎯 2026 Goals

![Progress](https://img.shields.io/badge/Progress-5%2F8%20complete-4F46E5?style=flat-square)

- [x] Strengthen C++ & DSA
- [x] Build real-world projects
- [x] Explore cyber security
- [x] Participate in hackathons
- [x] Contribute to open source
- [ ] Land a cyber security role
- [ ] Become industry-ready
- [ ] Build advanced security projects

---

<p align="center"><sub>Always open to conversations about security, AI, and building useful things.</sub></p>
<p align="center">
  <img src="https://komarev.com/ghpvc/?username=xyresiiic&label=Profile%20Views&color=4F46E5&style=flat-square" alt="Profile views">
</p>
