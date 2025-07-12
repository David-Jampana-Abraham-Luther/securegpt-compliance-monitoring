# securegpt-compliance-monitoring
An intelligent agent-based system that checks system logs for cybersecurity compliance based on NIST standards. It uses SecureGPT and AWS Lambda to detect violations, create service tickets, and store the results automatically.

# SecureGPT Compliance Monitoring 🚀

This project is part of a larger modular cybersecurity solution developed by the **Cyber Sentinel** team. It focuses on automated compliance monitoring of log datasets using SecureGPT, ensuring adherence to NIST standards such as:

- NIST SP 800-53 Rev. 5
- NIST SP 800-92
- NIST SP 800-171 Rev. 2
- NIST Cybersecurity Framework (CSF)

## 🧠 Built with Agentic AI
Two SecureGPT-powered AWS Lambda agents were developed:
- **Lambda 1: Compliance Monitoring Agent** – Analyzes logs from S3 buckets via SecureGPT to classify violations.
- **Lambda 2: Jira Ticketing Agent** – Automatically raises service tickets for non-compliant log entries in Jira.

## 🗂️ Input Datasets
- Simulated Server Logs (84 KB)
- HDFS Logs (291 KB)
- Real Server Logs (2.4 MB)

## 🎯 Features
- Real-time NIST compliance analysis
- SecureGPT Chain-of-Thought and Reflexion prompting
- Auto-generation of Jira tickets for policy violations
- Scalable S3 and Lambda architecture

## 📈 Evaluation Results
- **Accuracy**: 85–95%
- **F1 Score**: 0.89
- **Test Cases**: Edge-case handling, large datasets, duplicate ticket prevention, and empty log handling

## 📦 Tech Stack
- AWS Lambda
- S3 Buckets
- SecureGPT API
- Jira API
- Python (boto3, requests)

## 📌 Future Work
- Expand to real-time streaming data
- Add multi-model support (hybrid AI agents)
- Integrate learning loop for adaptive compliance updates


