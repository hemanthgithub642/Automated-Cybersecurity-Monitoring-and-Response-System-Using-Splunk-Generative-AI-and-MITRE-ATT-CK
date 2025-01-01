# Automated Cybersecurity Monitoring and Response System

## Overview
This project is designed to automate threat detection, analysis, and response in cybersecurity operations. By integrating **Splunk**, **Generative AI**, and the **MITRE ATT&CK framework**, it provides a real-time security monitoring system to identify threats, generate detailed reports, and automate incident response actions, effectively reducing cyber risks.

---

## Features
- **Real-Time Threat Detection**: Uses Splunk to monitor system logs and identify potential cyber threats.
- **Generative AI Reporting**: Automatically generates detailed, easy-to-understand incident reports using AI tools.
- **Automated Incident Response**: Executes automated actions (e.g., blocking malicious IPs) to mitigate risks.
- **MITRE ATT&CK Mapping**: Maps detected threats to MITRE ATT&CK techniques for detailed analysis and response.

---

## Technologies Used
- **Splunk**: For log monitoring, analysis, and detection.
- **Python**: For automating workflows and integrating AI tools.
- **Generative AI**: Tools like Hugging Face or OpenAI APIs for report generation.
- **MITRE ATT&CK**: Framework for mapping and understanding attack techniques.
- **Kali Linux**: For simulating real-world cyberattacks.
- **Ubuntu**: Operating system for deploying tools and scripts.

---

## Objectives
- Detect potential threats in real-time using Splunk.
- Automate the generation of AI-based incident reports for faster analysis.
- Map threats to MITRE ATT&CK techniques for improved understanding.
- Automate response actions to reduce risk and impact of cyberattacks.

---

## Installation and Setup

### Prerequisites
1. **Operating System**: Ubuntu (preferred), Windows 11 for development.
2. **Tools Required**:
   - Splunk Free (Download: [https://www.splunk.com/](https://www.splunk.com/))
   - Python 3.x
   - Hugging Face/OpenAI API access
   - MITRE ATT&CK Navigator
   - VirtualBox (if simulating attacks on Kali Linux/Ubuntu)

### Step-by-Step Guide
1. **Install Splunk**
   - Follow [Splunk Installation Guide](https://docs.splunk.com/) to set up Splunk on Ubuntu.
   - Configure log inputs for system monitoring.

2. **Set Up Python Environment**
   - Install Python on Ubuntu:
     ```bash
     sudo apt update
     sudo apt install python3 python3-pip
     ```
   - Install required libraries:
     ```bash
     pip install requests pandas openai
     ```

3. **Configure Generative AI**
   - Register for Hugging Face or OpenAI API.
   - Add API keys in the Python scripts.

4. **Install MITRE ATT&CK Navigator**
   - Use the online version or deploy it locally for mapping threats.

5. **Simulate Attacks**
   - Use Kali Linux to simulate attacks (e.g., brute force, phishing).

---

## Usage
1. **Run Splunk Queries**
   - Use SPL (Splunk Query Language) to analyze logs and detect threats.

2. **Generate AI Reports**
   - Run the `generate-report.py` script to create AI-driven incident reports.

3. **Automate Responses**
   - Use `incident-response.py` to trigger automated actions like blocking IPs or sending alerts.

4. **Analyze with MITRE ATT&CK**
   - Map detected threats to MITRE ATT&CK techniques for better understanding and response planning.

---

## Project Workflow
1. **Log Monitoring**: Splunk collects and analyzes logs.
2. **Threat Detection**: SPL queries identify anomalies and potential attacks.
3. **Report Generation**: Generative AI summarizes incidents in reports.
4. **Automated Response**: Python scripts execute predefined actions.
5. **Attack Mapping**: Detected threats are analyzed using MITRE ATT&CK.

---

## Results
- Real-time detection and response to cyber threats.
- Automated and AI-driven incident reporting.
- Improved visibility and understanding of attacks through MITRE ATT&CK mapping.

---

## Challenges Faced
- Setting up data ingestion pipelines in Splunk.
- Refining detection queries to reduce false positives.
- Ensuring AI-generated reports are clear and actionable.

---

## Future Enhancements
- Integrate more advanced attack simulations.
- Use machine learning for anomaly detection in logs.
- Add support for additional log sources like cloud environments.


