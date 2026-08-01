---
title: "Shubham Raj — GitHub Profile README"
---

<p align="center">
  <img src="https://img.shields.io/badge/Status-Open%20to%20opportunities-2bffc6?style=for-the-badge&logo=briefcase&logoColor=0b1220" alt="Open to opportunities" />
  <img src="https://img.shields.io/badge/Role-Software%20Development%20Engineer-7c5cff?style=for-the-badge&logo=dev.to&logoColor=ffffff" alt="Role" />
  <img src="https://img.shields.io/badge/Location-India-1e90ff?style=for-the-badge&logo=mapbox&logoColor=fff" alt="Location" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=28&lines=Shubham+Raj+%7C+Software+Development+Engineer;C%2B%2B+%7C+Python+%7C+Cloud+%7C+Machine+Learning&center=true&width=760&height=60&color=7c5cff" alt="Typing Header" />
</p>

<p align="center">
  <strong style="font-size:14px; color:#9aa0a6;">Final-year B.Tech Computer Science • Seeking SDE roles • Open Source Contributor • System Design & Cloud enthusiast</strong>
</p>

---

## Summary

- Name: Shubham Raj
- Current: Final-year B.Tech — Computer Science
- Looking for: Software Development Engineer (Backend / Cloud / ML-focused roles)
- Core strengths: Data Structures & Algorithms, Backend Development, Cloud (AWS), C++ & Python, ASP.NET MVC
- Seeking: Full-time SDE roles | Internships & Open Source collaboration
- Location: India (open to remote & relocation)

---

<p align="center">
  <a href="https://www.linkedin.com/in/shubham-raj-a0979a289/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-Profile-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://github.com/er-shubham-raj" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-er--shubham--raj-161b22?style=flat-square&logo=github&logoColor=white" alt="GitHub" />
  </a>
  <a href="mailto:er.rajshubham@gmail.com">
    <img src="https://img.shields.io/badge/Email-er.rajshubham%40gmail.com-7c5cff?style=flat-square&logo=gmail&logoColor=white" alt="Email" />
  </a>
</p>

---

<p align="center">
  <img src="https://img.shields.io/badge/C%2B%2B-Modern%20C%2B%2B-2bffc6?style=for-the-badge&logo=c%2B%2B&logoColor=000" alt="C++" />
  <img src="https://img.shields.io/badge/Python-3.11-1e90ff?style=for-the-badge&logo=python&logoColor=fff" alt="Python" />
  <img src="https://img.shields.io/badge/ASP.NET-MVC-7c5cff?style=for-the-badge&logo=dotnet&logoColor=fff" alt="ASP.NET MVC" />
  <img src="https://img.shields.io/badge/Cloud-AWS-00d1b2?style=for-the-badge&logo=amazon-aws&logoColor=fff" alt="AWS" />
  <img src="https://img.shields.io/badge/Machine%20Learning-ML-5dfbcb?style=for-the-badge&logo=TensorFlow&logoColor=fff" alt="ML" />
</p>

---

### About Me

I am a final-year B.Tech Computer Science student focused on building reliable, scalable backend systems and data-driven applications. I bring a strong foundation in algorithms and systems thinking, combined with hands-on experience in backend frameworks, cloud services (AWS), and machine learning pipelines. I contribute to open-source projects and prepare for industry roles in software engineering and cloud-native systems.

Key attributes:
- Strong foundation in DSA, OOP, and System Design
- Backend-first mindset: APIs, authentication, data modeling, and performance
- Cloud-aware: infrastructure fundamentals, serverless basics
- Practical engineering: unit testing, CI/CD, observability
- Product-oriented collaboration with emphasis on performance and UX

---

<table width="100%">
  <tr>
    <td width="50%" valign="top">

### Skills — Programming
- C++ (STL, modern patterns)
- Python (scripting, ML pipelines)
- Java
- C# (.NET ecosystem)
- SQL (relational design & queries)

### Web & APIs
- HTML, CSS, JavaScript
- ASP.NET MVC (enterprise patterns)
- REST API design & authentication

### Databases
- MySQL
- MongoDB

    </td>
    <td width="50%" valign="top">

### Cloud & DevOps
- AWS: EC2, S3, IAM, Lambda, Route53
- Docker (containerization & images)
- Basic CI/CD and deployment pipelines

### Tools
- Git & GitHub workflows
- VS Code, Visual Studio
- Postman, Docker

### Core Subjects
- Data Structures & Algorithms (DSA)
- Object-Oriented Programming (OOP)
- Database Management Systems (DBMS)
- Operating Systems (OS)
- Computer Networks
- System Design

    </td>
  </tr>
</table>

---

### Current Focus

- Advanced algorithmic problem solving and pattern recognition
- System Design fundamentals and architecture patterns
- Distributed systems principles and failure modes
- Microservices: API gateways, observability, scaling
- Docker & Kubernetes essentials
- Production-grade practices: monitoring, logging, resilience

### Learning Roadmap
<details>
  <summary>Click to expand: Learning plan & priorities</summary>

  - Advanced DSA: graphs, trees, segment trees, suffix arrays, heavy-light decomposition
  - System Design: database partitioning, caching, message queues, rate limiting
  - Distributed Systems: consensus algorithms (Raft/Paxos), replication strategies
  - Microservices: design for idempotency, eventual consistency, and service contracts
  - Containers & Orchestration: multi-stage Docker builds, Kubernetes patterns
  - Cloud: IaC basics, serverless pattern design (AWS Lambda), security best practices
  - ML: experimenting with feature stores, model serving, and inference latency optimization

</details>

---

## Selected Projects

Below are project summaries with technical highlights. Expand each for details, design notes, and implementation pointers.

### 1) SR Library — Enterprise Smart Library Management System
- Role: Full-stack design & backend implementation
- Tech: C#, ASP.NET MVC, SQL Server, Bootstrap
- Features:
  - Authentication & Authorization (Role-based)
  - Book Issue / Return workflow with logging
  - Fine management system & overdue tracking
  - Administrative Dashboard & Reports
- Highlights:
  - Normalized DB schema with indexes for search
  - Secure password storage and session handling
  - Reports exportable as CSV/PDF for administrative workflows

<details>
  <summary>SR Library — Technical details</summary>

  Architecture & design notes:
  - MVC pattern with repository and service layers for testability
  - Stored procedures for complex report generation and aggregate computations
  - Caching layer for commonly requested book metadata
  - Unit tests for core services and integration tests for DB interactions

  Implementation checklist:
  - [x] Authentication & roles
  - [x] Book lifecycle management
  - [x] Dashboard & reporting
  - [x] Export utilities

  Future improvements:
  - Migrate to microservices for scale
  - Add async background processing for bulk operations
  - Add role-based audit trail and immutable logs

</details>

---

### 2) VitalVision — AI Patient Risk Prioritization
- Role: Data engineer & ML modeler
- Tech: Python, Flask, Pandas, Scikit-learn
- Features:
  - Risk prediction model for triage prioritization
  - REST API for predictions and batch scoring
  - Data pipeline for cleaning and feature engineering
- Highlights:
  - Emphasis on model explainability (feature importance)
  - Dockerized inference service for reproducible deployments

<details>
  <summary>VitalVision — Technical details</summary>

  - Modeling: tried logistic regression and tree-based ensembles, evaluated via ROC-AUC and calibration
  - Preprocessing: robust handling of missing clinical fields, reproducible feature pipelines
  - Deployment: Flask API with input validation and rate limiting
  - Observability: model monitoring for input drift (basic approach)

  Lessons learned:
  - Feature standardization and consistent schema saved iteration time
  - Transparent model outputs (probability, top features) improved clinician trust

</details>

---

### 3) Product Management System
- Tech: ASP.NET MVC, SQL Server
- Features: CRUD, authentication, role-based access control
- Focus: pragmatic architecture for a small enterprise product management workflow

<details>
  <summary>Product Management System — Technical details</summary>

  - Patterns: repository and unit-of-work, dependency injection
  - Security: role checks at controller & service layer; action filters
  - Logging: structured logs for auditing user actions

</details>

---

### Projects — code & diagrams
- For code samples and architecture diagrams, raise an issue or open a PR in this repo. I will provide design rationales, sequence diagrams (Mermaid), and code walkthroughs on request.

---

<!-- GitHub statistics & visual blocks -->
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=er-shubham-raj&show_icons=true&theme=radical&hide_border=true&bg_color=0d1117" alt="GitHub Stats" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=er-shubham-raj&theme=react-dark&hide_border=true" alt="Streak Stats" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=er-shubham-raj&hide_border=true&theme=radical&langs_count=8&layout=compact" alt="Top Languages" />
</p>

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=er-shubham-raj&theme=discord&no-frame=true&margin-w=8" alt="Trophies" />
</p>

<p align="center">
  <img src="https://activity-graph.herokuapp.com/graph?username=er-shubham-raj&theme=react-dark&hide_border=true&area=true" alt="Contribution Graph" />
</p>

---

### Competitive Programming & Coding Profiles

<p align="left">
  <a href="https://leetcode.com/u/Shubham-Raj/" target="_blank">
    <img src="https://img.shields.io/badge/LeetCode-Shubham--Raj-ffa116?style=flat&logo=leetcode&logoColor=fff" alt="LeetCode" />
  </a>
  <a href="https://www.hackerrank.com/YOUR_HACKERRANK_USERNAME" target="_blank">
    <img src="https://img.shields.io/badge/HackerRank-YOUR_HACKERRANK_USERNAME-2EC866?style=flat&logo=hackerrank&logoColor=fff" alt="HackerRank" />
  </a>
  <a href="https://www.codechef.com/users/YOUR_CODECHEF_USERNAME" target="_blank">
    <img src="https://img.shields.io/badge/CodeChef-YOUR_CODECHEF_USERNAME-005aa7?style=flat&logo=codechef&logoColor=fff" alt="CodeChef" />
  </a>
  <a href="https://auth.geeksforgeeks.org/user/YOUR_GFG_USERNAME/profile" target="_blank">
    <img src="https://img.shields.io/badge/GeeksforGeeks-YOUR_GFG_USERNAME-35bf6b?style=flat&logo=geeksforgeeks&logoColor=fff" alt="GeeksforGeeks" />
  </a>
</p>

---

### Achievements & Certifications

- [Placeholder] Winner — College Hackathon (Add title & date)
- AWS Cloud — add certification link here
- DSA specialization — add certificate link

<details>
  <summary>Certifications — Expand for details</summary>

  - AWS Certified Cloud Practitioner — [link to cert]
  - Data Structures & Algorithms — [link to cert or course]
  - Additional certifications (list provider & link)

</details>

---

### Open Source & Hackathons

- Contributor to small and medium open-source projects focused on backend reliability and API improvements
- Participated in college-level hackathons and online hackathons; experience with product-driven prototyping

<details>
  <summary>Open source highlights</summary>

  - Example PR: Improved API performance by optimizing DB queries (link placeholder)
  - Example PR: Added input validation and tests to public utility library (link placeholder)

</details>

---

### Experience (Academic / Project)

- Student Developer — college projects and real-world internships (describe role & responsibilities in repo or resume)
- Freelance / volunteer backend work: API modules, ETL scripts, small infra automation

---

## Recruiter-friendly snapshot

- Title: Software Development Engineer — Backend / Cloud
- Education: B.Tech - Computer Science (Final Year)
- Location: India — Available for relocation & remote
- Preferred languages: C++, Python, C#
- Cloud: AWS basics to intermediate (EC2, S3, Lambda, IAM)
- Looking for: Full-time SDE roles with a focus on backend, platform, or ML infra

---

### Resume & Contact

- Resume: add a public link (e.g., /resumes/Shubham-Raj-Resume.pdf)
- Email: er.rajshubham@gmail.com
- LinkedIn: https://www.linkedin.com/in/shubham-raj-a0979a289/
- GitHub: https://github.com/er-shubham-raj

For recruiters: Please email role details with required tech stack and I’ll respond with availability and a tailored resume.

---

### Fun Facts

- Favorite languages: C++ for performance, Python for rapid prototyping
- I enjoy system design reading and building small, production-like services
- Coffee and problem-solving fuel my best coding sessions ☕️🧩

---

<p align="center">
  <img src="https://img.shields.io/badge/DSA-Strong-2bffc6?style=for-the-badge" />
  <img src="https://img.shields.io/badge/System%20Design-Learning-1e90ff?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Cloud-AWS-7c5cff?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Backend-APIs-00d1b2?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Testing-&-CI-CD-5dfbcb?style=for-the-badge" />
</p>

---

<details>
  <summary>More — Tools, Libraries, Interests</summary>

- Version control: Git, GitHub Actions basics
- Editors: VS Code, Visual Studio
- Libraries: Pandas, Scikit-learn
- Testing: unit testing patterns & integration checks
- Interests: Observability, reliability, ML inference at scale

</details>

---

### Collaboration & Contribution

I welcome:
- Mentorship, code reviews, and pair-programming sessions
- Open-source maintainers seeking contributors in backend or data tooling
- Recruiters hiring for backend/cloud/ML infra

How to collaborate:
- Open an issue in a repo you want help with
- Ping me via LinkedIn or email with context and tech stack
- Share diagrams or sample data for deeper technical discussions

---

### Privacy & Accessibility

- This README is built for clarity and accessibility: structured sections, clear headings, and concise bullets for quick scanning
- Need a text-only or accessible resume? Email and I’ll provide one

---

<!-- Animated wave footer (subtle) -->
<p align="center">
  <svg width="100%" height="120px" viewBox="0 0 1200 120" preserveAspectRatio="none" style="display:block;">
    <defs>
      <linearGradient id="grad" x1="0" x2="1">
        <stop offset="0%" stop-color="#7c5cff" stop-opacity="0.15">
          <animate attributeName="stop-opacity" values="0.15;0.35;0.15" dur="6s" repeatCount="indefinite" />
        </stop>
        <stop offset="50%" stop-color="#00d1b2" stop-opacity="0.12">
          <animate attributeName="stop-opacity" values="0.12;0.30;0.12" dur="6s" repeatCount="indefinite" />
        </stop>
        <stop offset="100%" stop-color="#1e90ff" stop-opacity="0.1">
          <animate attributeName="stop-opacity" values="0.1;0.25;0.1" dur="6s" repeatCount="indefinite" />
        </stop>
      </linearGradient>
    </defs>

    <path d="M0,40 C150,120 350,0 600,40 C850,80 1050,0 1200,40 L1200,120 L0,120 Z" fill="url(#grad)">
      <animateTransform attributeName="transform" attributeType="XML" type="translate" from="-15 0" to="15 0" dur="6s" repeatCount="indefinite" />
    </path>

    <path d="M0,44 C160,100 360,10 600,46 C840,80 1040,10 1200,44 L1200,120 L0,120 Z" fill="#0b1220" fill-opacity="0.04"></path>
  </svg>
</p>

<p align="center" style="font-size:12px; color:#9aa0a6;">Built with clarity and performance in mind — Shubham Raj • © 2026</p>

---

<details>
  <summary>Repository notes, license & contribution guide</summary>

- License: MIT (change as preferred)
- Contribution: Open an issue or PR with a short description
- Repo structure suggestion:
  - /projects — project READMEs & diagrams
  - /resumes — store resume PDF if desired
  - /diagrams — architecture diagrams (SVG/Mermaid)

</details>

<!-- End of README -->
