# AI-Powered Cybersecurity Threat Intelligence System

## Overview
This repository contains a multi-agent AI system that automates cybersecurity threat analysis by leveraging:
- CrewAI for orchestrating AI agents
- LangChain-Groq (Llama 3-70B) for AI-powered reasoning
- EXA API for real-time cybersecurity intelligence search

## Key Features
- **Threat Intelligence Gathering** – Fetches the latest malware trends and cyberattacks
- **Vulnerability Research** – Identifies and analyzes new CVEs (Common Vulnerabilities and Exposures)
- **Incident Response Advisor** – Recommends mitigation strategies for detected threats
- **AI-Generated Cybersecurity Reports** – Summarizes all findings into a structured Threat Intelligence Report

## How It Works
1. **Threat Analyst Agent** – Uses EXA API to fetch the latest cybersecurity threats
2. **Vulnerability Researcher Agent** – Retrieves new software vulnerabilities and security flaws
3. **Incident Response Advisor Agent** – Provides remediation strategies for identified threats
4. **Cybersecurity Report Writer Agent** – Generates a structured cybersecurity report

## Tech Stack
- Python
- CrewAI
- LangChain-Groq (Llama 3-70B)
- EXA API

## Getting Started

### Installation
```bash
pip install 'crewai[tools]' langchain-groq exa_py
```

### Run the System
```bash
python cybersecurity_ai.py
```

**Note:** Set up API keys for `GROQ_API_KEY` and `EXA_API_KEY` before running.

## Sample Output
```
Cybersecurity Threat Intelligence Report:

Top Threats
1. Emotet Malware Campaign – Highly active malware spreading through phishing
2. Ransomware Attacks on Healthcare – Critical cyberattacks demanding large ransoms
3. Apache Log4j Vulnerability Exploitation – Zero-day vulnerability actively targeted

Latest Security Vulnerabilities (CVEs)
- CVE-2024-12345: High-risk vulnerability in Apache
- CVE-2024-67890: Microsoft Windows privilege escalation flaw

Recommended Actions
- Implement robust email security measures
- Conduct regular vulnerability assessments
- Enhance endpoint security with AI-driven threat detection
```

## Use Cases
- **SOC Teams** – Automate threat intelligence gathering
- **Cybersecurity Researchers** – Generate structured vulnerability reports
- **Enterprises** – Improve incident response strategies

## Contributing
Feel free to fork, open issues, and contribute to enhance this AI-powered cybersecurity tool.
