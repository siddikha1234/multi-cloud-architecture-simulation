# 🧩 Multi-Cloud Interoperability Demo (Simulated)

This document outlines a simulated workflow demonstrating interoperability between AWS and Google Cloud.

---

## 🛠 Architecture Summary

- **AWS S3** stores a file (e.g., log or data dump).
- **AWS Lambda** is triggered when a new file is uploaded to S3.
- **Lambda** sends metadata (filename, timestamp) via HTTP POST to a **Google Cloud Function**.
- **GCP Cloud Function** receives the data and inserts it into **BigQuery** for analysis.

---

## 📡 Communication

- **Method:** REST API (JSON over HTTPS)
- **Security:** Simulated with API Key or IAM role assumption
- **Trigger:** AWS Lambda (event-driven)

---

## 🔁 Flow (Simulated)

1. 📥 File uploaded to AWS S3  
2. ⚙️ Lambda triggered → Sends API call  
3. 🌐 Google Cloud Function receives data  
4. 📊 Data logged/stored in BigQuery  

---

This setup demonstrates the ability to interconnect cloud services across different platforms for real-time processing and analytics.
