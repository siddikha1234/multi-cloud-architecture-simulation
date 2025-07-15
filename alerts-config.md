# 🔔 Simulated Alert Configurations

This file simulates alert rules that you would typically configure using AWS CloudWatch, Google Cloud Monitoring, or Azure Monitor.

---

## 🚨 Alert Rules

### 1. CPU Usage Alert
- Condition: CPU Utilization > 80% for 5 consecutive minutes
- Notification: Email sent to admin@example.com

### 2. Disk Space Alert
- Condition: Disk usage > 90%
- Notification: Slack channel #infrastructure-alerts

### 3. HTTP 5xx Errors
- Condition: More than 50 HTTP 5xx errors within 10 minutes
- Notification: PagerDuty incident triggered

---

## 🛠️ Simulated Platform Tools

- AWS CloudWatch: Using Metric Alarms and SNS
- Google Cloud Monitoring: Using Alert Policies and Notification Channels
- Azure Monitor: Using Metric Alerts and Action Groups

📌 Note: These are simulated configurations for internship submission purposes only.
