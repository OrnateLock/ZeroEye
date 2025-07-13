# ZeroEye  
An AI-powered Cybersecurity Copilot by OrnateLock

---

## What is ZeroEye?

ZeroEye is an upcoming open-source cybersecurity tool that uses artificial intelligence to understand, explain, and help respond to system-level security logs.

The goal is to build a virtual cybersecurity assistant that can:

- Read and interpret raw system and server logs
- Translate logs into plain English explanations
- Assess the severity of each event
- Recommend (or eventually perform) defensive actions
- Store and visualize activity for ongoing monitoring

ZeroEye is designed for small teams, sysadmins, security learners, and developers who want clarity, simplicity, and support in understanding their system behavior and potential threats.

---

## Project Status

This project is in the early research and planning stage.

Development has not yet started.  
Initial steps include studying Linux logs, understanding AI prompt engineering, and setting up the core backend structure.

---

## Why ZeroEye?

Many small companies and developers do not have access to full-time security teams or expensive tools like commercial SIEMs. Logs are often difficult to interpret, leading to missed threats or wasted time.

ZeroEye aims to solve this by:

- Providing clear, understandable threat insights using AI
- Offering lightweight monitoring without complex setup
- Automating basic threat detection and recommendation workflows

---

## Key Concepts (Target Features)

- Log ingestion and parsing (starting with Linux auth logs)
- Integration with AI (e.g., GPT) to explain log events
- Scoring and categorizing potential security risks
- Optional auto-response logic (block IP, kill process, notify admin)
- Log storage and basic dashboard UI (optional frontend)

---

## Target Users

- IT admins or DevOps in startups and small businesses
- Solo developers running their own servers
- Cybersecurity students and open-source contributors
- Projects that need an affordable alternative to heavy SIEM tools

---

## Tech Stack (Planned)

- Python for backend logic and log processing
- FastAPI for creating RESTful services
- OpenAI API for AI explanations
- MongoDB Atlas for storing logs and results
- Linux-based logs as the primary data source
- Optional frontend with Streamlit or React

---

## Created By

**OrnateLock** – Building AI-first tools for modern cybersecurity  
Founded and maintained by Amal Tom

Follow along as ZeroEye grows from idea to working prototype.

