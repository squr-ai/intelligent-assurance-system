# Intelligent Assurance System (IAS) for Autonomous AI Pentesters

This repository contains the artifacts and example notebooks for our study **“Towards Intelligent Assurance for Autonomous AI Pentesters: Concurrent Compliance Auditing and Self‑Augmentation via Execution Trace Analysis”**. The core deliverable is `main.ipynb`, which demonstrates:

- Ingesting LangSmith execution traces from a fully autonomous AI Pentester  
- Extracting and summarizing individual tool‑call steps  
- Auditing each step for compliance with the EU AI Act and GDPR using Google’s GenAI SDK (Gemini models)  
- Generating compact corrective “feedback policies” to steer the Pentester’s next prompt  
- (Proof‑of‑Concept) Creating imperative policies for retrofitting the Pentester’s prompt context  
- Displaying results and “Lessons Learned” in‑notebook  


---

## 🔧 Prerequisites

- Python 3.8+   
- A valid Google GenAI API key (Gemini Developer API)  



