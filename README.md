# Joell Alex — Software Development Engineer Intern

**Mumbai, Maharashtra, India • B.Tech, Computer Science & Business Systems (Expected 2027)**

---

## Summary

Software Development Engineer Intern with experience shipping production-grade backend APIs and real-time systems. Proficient in Go and Python, I build AI-assisted pipelines with a focus on reliability, system validation, and error handling. Interested in systems, developer infrastructure, and product engineering.

---

##  Work Experience

### Neubitat
**Software Development Intern** | Remote | Dec 2025 - Present
- Built and shipped React + Next.js frontend features for a real-time chess platform, directly supporting live gameplay and puzzle interactions.
- Designed and implemented production Python backend APIs with clear contracts to support chess puzzles, scoring logic, and multiplayer game state.
- Integrated AI-powered OCR pipelines using OpenAI and Gemini APIs, designing validation, normalization, and post-processing logic to ensure downstream systems only consumed structured, reliable chess move data (SAN).
- Implemented real-time state synchronization using WebSockets, handling partial failures and inconsistent client state during live gameplay.

### Ohey Inc.
**MLOps Engineer Intern** | Remote (San Francisco) | Feb 2026 - Present
- Architected and deployed an end-to-end observability stack on a cloud VPS using Prometheus and Grafana, configuring scrape targets, jobs, and port bindings while organizing dashboards across monitoring layers.
- Built ML monitoring dashboards for 10+ models (XGBoost, LightGBM, HistGBM, MLP, and ensemble variants), defining metrics and visualization panels for inference latency and model-serving performance.
- Instrumented API and infrastructure observability, tracking request latency, queue lag, CPU utilization, memory usage, and disk I/O across the model-serving pipeline.
- Extended monitoring to remote infrastructure by deploying node_exporter on a secondary VPS, configuring it as a Prometheus scrape target, and running Prometheus and Grafana as systemd services for automatic startup.

### VoiceHelden
**Automation Engineer Intern** | Remote (Netherlands) | Feb 2026 - Present
- Built an end-to-end lead enrichment pipeline in n8n that ingests CSV datasets of company domains, orchestrates an email-scraping service, and outputs structured contact data to Google Sheets, eliminating manual lead research.
- Forked and re-engineered an open-source email scraping service, replacing sequential requests with a concurrent ThreadPoolExecutor (5 workers) and persistent HTTP sessions, reducing per-domain scrape time from ~20 minutes to ~5 minutes; integrated output into Google Sheets to eliminate manual lead research.
- Implemented custom JavaScript parsing nodes to normalize inconsistent JSON output across multiple LLM providers (Groq, OpenAI), ensuring pipeline reliability across provider-level response variance.

---

##  Education

**Mukesh Patel School of Technology Management & Engineering** | Jun 2023 - Jun 2027
- B.Tech, Computer Science & Business Systems
- GPA: 3.73/4
- Coursework: Data Structures and Algorithms, Object-Oriented Programming, Python Programming, Java Programming, Game Development Fundamentals, C++ Programming

---

##  Skills & Technologies

**Programming Languages:** Golang, Python, Java, C++, SQL, JavaScript, TypeScript

**Frontend:** React, Next.js

**Backend & Systems:** REST APIs, WebSockets, Docker, Linux, API design

**Development Tools:** VSCode, Jupyter Notebooks, Git, GitHub, Gitlab

**Databases:** MySQL, MongoDB

**Operating Systems:** Windows, macOS, Ubuntu

**AI / APIs:** OpenAI API, Gemini API

**Domains:** Backend Systems, AI Integration, Data-Driven Automation, Systems Design

---

##  Projects

### Traffic Violation Detection Bot
*ROS2, OpenCV, MediaPipe, Ubuntu* | Aug 2025 - Nov 2025
- Developed a modular real-time traffic monitoring system using ROS2 with multi-node architecture and asynchronous communication.
- Implemented event-driven pipelines using ROS2 Topics, Services, and Actions to coordinate camera ingestion, detection, and violation handling.
- Applied computer vision techniques using OpenCV and MediaPipe for live object tracking and threshold-based violation detection.
- Deployed and tested the system on Ubuntu 22.04 (VMware), demonstrating scalability and modular system design.

### AI-Powered Symptom & Medicine Advisor
*Python, Gemini API, FDA API, MySQL* | Feb 2025 - Mar 2025
- Built a Python-based system that processes unstructured user input into validated, structured health data using the Gemini API, while enforcing strict non-diagnostic constraints.
- Integrated the FDA API to fetch verified medicine information and safety data for user-facing recommendations.
- Designed a MySQL-backed data layer to cache symptom and medicine mappings, reducing repeated API calls and improving response latency.
- Delivers verified medicine recommendations with 85% accuracy.

### GitHub Automated Code Review Bot
*Next.js, Octokit, Gemini API* | Jan 2026 - Present
- Built a GitHub App webhook service in Next.js that listens to pull request events and automatically triggers an AI code review on every opened PR.
- Implemented GitHub App installation authentication using Octokit, enabling secure per-repository API access without exposing static credentials.
- Developed a context-aware review pipeline that retrieves both PR diffs and full file contents, allowing the model to detect deeper bugs beyond surface-level changes.
- Added file filtering and structured Gemini prompts to exclude non-reviewable files and restrict output to bugs, security risks, and critical performance issues.

### Knight's Adventure (Hack-and-Slash Game)
*Godot Engine, GDscript* 
- Published for macOS & Windows; 100+ downloads, 15k+ Instagram views.
- Designed tutorials and accessibility for young players (ages 7+).

---

##  Connect

- [LinkedIn](https://www.linkedin.com/in/joell-alex/)
- **Email:** joellalex922@gmail.com

---

##  Interests & Impact

- Guided 100+ students in Lua scripting and game development during a Rancho Labs internship.
- Passionate about building AI-driven tools to make health and education more accessible.
- Motto: *"Code that teaches, builds, and inspires."*

---

*Seeking opportunities in backend engineering, systems design, automation, and AI integration. Let's connect!*
