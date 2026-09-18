<p align="center">
  <img src="https://raw.githubusercontent.com/hrshagarwal/hrshagarwal/main/github_banner.png" alt="Harsh Agarwal" width="100%" />
</p>

<h1 align="center">
  Hi, I'm Harsh Agarwal 
  <img src="wave.gif" width="30px" height="30px" />
</h1>

<p align="center">
  <strong>Backend development and exploring applied computer vision</strong><br/>
  C++ · Python · Node.js · CS minor @ IIT Jammu
</p>

<p align="center">
  <a href="https://harshagarwaliitj.vercel.app/">
    <img src="https://img.shields.io/badge/Portfolio-000000?style=flat-square&logo=vercel&logoColor=white" alt="Portfolio" />
  </a>
  <a href="https://www.linkedin.com/in/harshagarwal22/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:2024uce0050@iitjammu.ac.in">
    <img src="https://img.shields.io/badge/Email-333333?style=flat-square&logo=gmail&logoColor=white" alt="Email" />
  </a>
</p>

---

I'm a pre-final year student at IIT Jammu — Civil Engineering by degree, Computer Science by minor and by what I actually spend my time on. Most of that time goes into backend engineering: API design, auth and access control, data modelling, and the unglamorous work of making a system hold up under real users.

I also explore applied ML, particularly computer vision and speaker recognition, with a focus on building and evaluating embedding-based pipelines for real-world applications.


---

## Experience

**Software Developer Intern** — Brahmaputra Board, Ministry of Jal Shakti (Govt. of India) · *May 2026 – Present*

Architecting the production backend for a Government Productivity Management System — the prototype that won Smart India Hackathon 2025 — now being built out for a 195-employee statutory body.

- REST APIs in **Node.js / Express**, ingesting data from national platforms (eOffice, AEBAS, PFMS) into **MongoDB** and **PostgreSQL**
- A role-specific **KPI computation engine** across four officer tracks, replacing subjective annual appraisals with scoring derived from live system signals
- **OAuth SSO** via Government e-Pramaan with JWT sessions and hierarchy-aware **RBAC** across 6+ role levels
- Requirement gathering and SRS authoring directly with Ministry stakeholders

---

## Selected Projects

### ProxZero — AI-Powered Classroom Attendance

Marks an entire class from a single photograph. Built to make proxy attendance structurally impossible rather than just inconvenient, using face and voice biometrics.

**Stack:** Python · dlib · Resemblyzer · Librosa · Scikit-learn · NumPy · Supabase (PostgreSQL) · Streamlit

- Tightened the dlib 128-d ResNet face pipeline's nearest-neighbour L2 threshold from 0.6 → 0.42, with a 0.08 margin gate to reject look-alike faces
- Added a speaker-recognition mode — Resemblyzer 256-d d-vectors with Librosa silence segmentation — identifying multiple students from one classroom recording at 0.65 cosine similarity
- 5-table schema with bcrypt auth and QR self-enrollment; collapsed the dashboard from N+1 queries to a single round trip via PostgREST aggregation

[`Code`](https://github.com/hrshagarwal/ProxZero) · [`Live Demo`](https://proxzero.streamlit.app/)

### StayNest — Accommodation Marketplace

An Airbnb-style rental platform, built to get the boring parts right: authorization at the route layer, validation at the boundary, and sessions that survive a restart.

**Stack:** Node.js · Express 5 · MongoDB Atlas · Mongoose · Passport.js · Cloudinary · EJS

- 6 reusable Express middleware guards enforcing owner-only writes — authorization lives in the route layer, not the UI
- Migrated sessions from in-memory to MongoDB via connect-mongo, cutting session writes from one per request to one per 24 hours
- Joi request validation with centralized async error handling (custom `ExpressError`, `wrapAsync`), and Mongoose post-hooks cascading review deletion

[`Code`](https://github.com/hrshagarwal/StayNest) · [`Live Demo`](https://staynest-midq.onrender.com/listings)

---

## Achievements

**Winner — Smart India Hackathon 2025**, National Level  
**Department Rank 1**, IIT Jammu 
---

## 🛠️ Tech Stack

### Languages
<p>
  <img src="https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=white" />
  <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
</p>

### Backend
<p>
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white" />
  <img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white" />
  <img src="https://img.shields.io/badge/REST%20APIs-005571?style=for-the-badge" />
  <img src="https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white" />
  <img src="https://img.shields.io/badge/OAuth-4285F4?style=for-the-badge&logo=oauth&logoColor=white" />
  <img src="https://img.shields.io/badge/RBAC-6A1B9A?style=for-the-badge" />
</p>

### Databases
<p>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" />
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" />
  <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white" />
</p>

### Machine Learning / Computer Vision
<p>
  <img src="https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" />
  <img src="https://img.shields.io/badge/dlib-008000?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Resemblyzer-6C5CE7?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Librosa-FF6F61?style=for-the-badge" />
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" />
</p>

### Frontend
<p>
  <img src="https://img.shields.io/badge/React.js-61DAFB?style=for-the-badge&logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
  <img src="https://img.shields.io/badge/EJS-B4CA65?style=for-the-badge&logo=ejs&logoColor=black" />
</p>

### Tools
<p>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white" />
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" />
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" />
</p>

## GitHub

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=hrshagarwal&show_icons=true&theme=tokyonight&hide_border=true&hide_title=true" height="150" alt="GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=hrshagarwal&layout=compact&theme=tokyonight&hide_border=true&langs_count=6" height="150" alt="Top Languages" />
</p>

---



<p align="center">
  <a href="https://harshagarwaliitj.vercel.app/">Portfolio</a> ·
  <a href="https://www.linkedin.com/in/harshagarwal22/">LinkedIn</a> ·
  <a href="mailto:2024uce0050@iitjammu.ac.in">Email</a>
</p>
